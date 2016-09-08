#### Test 82912030f17cf99_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
09-08 16:01:43.213  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:01:43.219  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
09-08 16:01:43.261  1527  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 16:01:43.261  1527  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 16:01:43.262  1527  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:01:43.262  1527  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 16:01:43.283  3550  3854 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 16:01:43.283  3550  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jdm.a(PG:82)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jcs.o(PG:406)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jcn.a(PG:1379)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jcs.i(PG:143)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at blb.a(PG:3937)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at czp.a(PG:18188)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at czp.a(PG:9081)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at czq.run(PG:1686)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:01:43.283  3550  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jdj.a(PG:4091)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jdj.a(PG:1125)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jdm.a(PG:77)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	... 12 more
09-08 16:01:43.283  3550  3854 E HttpOperation: Caused by: faj: BadAuthentication
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at fal.a(PG:38)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	at jdj.a(PG:4089)
09-08 16:01:43.283  3550  3854 E HttpOperation: 	... 14 more
09-08 16:01:43.345  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 16:01:43.345  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 16:01:43.345  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:01:43.345  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
09-08 16:01:43.364  3550  3854 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 16:01:43.364  3550  3854 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jdm.a(PG:82)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jcs.o(PG:406)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jcn.a(PG:1379)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jcs.i(PG:143)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at hec.a(PG:42)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at hee.a(PG:102)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at czr.a(PG:65)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at kka.a(PG:108)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at czp.a(PG:19176)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at czp.a(PG:9081)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at czq.run(PG:1686)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:01:43.364  3550  3854 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jdj.a(PG:4091)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jdj.a(PG:1125)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jdm.a(PG:77)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	... 15 more
09-08 16:01:43.364  3550  3854 E HttpOperation: Caused by: faj: BadAuthentication
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at fal.a(PG:38)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	at jdj.a(PG:4089)
09-08 16:01:43.364  3550  3854 E HttpOperation: 	... 17 more
09-08 16:01:43.364  3550  3854 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 16:01:43.364  3550  3854 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at hec.a(PG:42)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at hee.a(PG:102)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at czr.a(PG:65)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at kka.a(PG:108)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jdj.a(PG:1125)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	... 15 more
09-08 16:01:43.364  3550  3854 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at fal.a(PG:38)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 16:01:43.364  3550  3854 E ExperimentLoader: 	... 17 more
09-08 16:01:43.500   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 320512, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
09-08 16:01:43.857  3855  3855 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 16:01:43.861  3855  3855 D AndroidRuntime: CheckJNI is OFF
09-08 16:01:43.896  3855  3855 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 16:01:43.940  3855  3855 I Radio-JNI: register_android_hardware_Radio DONE
09-08 16:01:43.960  3855  3855 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-08 16:01:43.964   876  1543 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-08 16:01:44.034   876  1543 I ActivityManager: Start proc 3865:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
09-08 16:01:44.041  3855  3855 D AndroidRuntime: Shutting down VM
09-08 16:01:44.180  3865  3865 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
09-08 16:01:44.207  3865  3865 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
09-08 16:01:44.215  3865  3865 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1774-1776)
09-08 16:01:44.215  3865  3865 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 16:01:44.234  3865  3865 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {129a1e2}
09-08 16:01:44.235  3865  3865 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 16:01:44.235  3865  3865 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-08 16:01:44.241  3865  3865 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-08 16:01:44.243  3865  3865 E SysUtils: ApplicationContext is null in ApplicationStatus
09-08 16:01:44.265  3865  3865 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 16:01:44.275  3865  3865 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 16:01:44.275  3865  3865 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-08 16:01:44.275  3865  3865 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 16:01:44.275  3865  3865 I Adreno  : Build Date                       : 10/20/15
09-08 16:01:44.275  3865  3865 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 16:01:44.275  3865  3865 I Adreno  : Local Branch                     : M14
09-08 16:01:44.275  3865  3865 I Adreno  : Remote Branch                    : 
09-08 16:01:44.275  3865  3865 I Adreno  : Remote Branch                    : 
09-08 16:01:44.275  3865  3865 I Adreno  : Reconstruct Branch               : 
,09-08 16:01:44.361   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4df0228:true
,09-08 16:01:44.414  3865  3865 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-08 16:01:44.429  3865  3865 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,09-08 16:01:44.473  3865  3902 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,09-08 16:01:44.482  3865  3889 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,09-08 16:01:44.517  3865  3902 I OpenGLRenderer: Initialized EGL, version 1.4
,09-08 16:01:44.540  1910  1910 I Keyboard.Facilitator: onFinishInput()
,09-08 16:01:44.587   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +466ms (total +571ms)
,09-08 16:01:44.716  3865  3865 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3865
,09-08 16:01:44.849  3865  3865 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-08 16:01:44.999  3865  3904 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1695811280
,09-08 16:01:45.006  3865  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-08 16:01:45.006  3865  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-08 16:01:45.006  3865  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-08 16:01:45.006  3865  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-08 16:01:45.006  3865  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-08 16:01:45.006  3865  3904 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd25a1 added. We now have 1 listener(s)
,09-08 16:01:45.010  3865  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,09-08 16:01:45.010  3865  3904 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:01:45.011  3865  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:01:45.011  3865  3904 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,09-08 16:01:45.015  3865  3904 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13efeb4 added. We now have 1 listener(s)
09-08 16:01:45.015  3865  3904 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:01:45.020  3865  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 16:01:45.020  3865  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-08 16:01:45.020  3865  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-08 16:01:45.020   876  1317 D WifiService: New client listening to asynchronous messages
,09-08 16:01:45.020  3865  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-08 16:01:45.020  3865  3904 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-08 16:01:45.024  3865  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:01:45.024  3865  3904 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,09-08 16:01:45.038  3865  3904 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:01:45.038  3865  3904 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:01:45.038  3865  3904 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-08 16:01:45.039  3865  3904 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:01:45.039  3865  3904 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-08 16:01:45.041  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:01:45.045  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:01:45.064  3865  3865 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-08 16:01:45.878  3865  3911 W jxcore-log: Initializing JXcore engine
,09-08 16:01:45.879  3865  3911 W jxcore-log: JXcore engine is ready
,09-08 16:01:45.916  3911  3911 W Thread-329: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,09-08 16:01:45.916  3911  3911 W Thread-329: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[11096]" dev="sockfs" ino=11096 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-08 16:01:45.916  3911  3911 W Thread-329: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-08 16:01:45.916  3911  3911 W Thread-329: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[29041]" dev="sockfs" ino=29041 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,09-08 16:01:45.930  3865  3911 W jxcore-log: Starting JXcore engine
,09-08 16:01:46.010  3865  3911 W jxcore-log: Platform android
09-08 16:01:46.010  3865  3911 W jxcore-log: 
,09-08 16:01:46.011  3865  3911 W jxcore-log: Process ARCH arm
09-08 16:01:46.011  3865  3911 W jxcore-log: 
,09-08 16:01:46.243  3865  3911 I jxcore-log: JXcore Cordova bridge is ready!
09-08 16:01:46.243  3865  3911 I jxcore-log: 
,09-08 16:01:46.243  3865  3911 W jxcore-log: JXcore engine is started
,09-08 16:01:46.254  3865  3904 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-08 16:01:46.259  3865  3865 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-08 16:01:47.675   876  1933 D NetlinkSocketObserver: NeighborEvent{elapsedMs=325237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,09-08 16:01:59.840  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-08 16:01:59.840  3865  3911 I jxcore-log: 
,09-08 16:01:59.843  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-08 16:01:59.843  3865  3911 I jxcore-log: 
,09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:01:59.856  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:01:59.864  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:01:59.870  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-08 16:01:59.870  3865  3911 I jxcore-log: 
,09-08 16:01:59.879  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-08 16:01:59.879  3865  3911 I jxcore-log: 
,09-08 16:02:00.240  3865  3911 I jxcore-log: Running unit tests
09-08 16:02:00.240  3865  3911 I jxcore-log: 
09-08 16:02:00.241  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:02:00.241  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@83f2c21 added. We now have 2 listener(s)
09-08 16:02:00.242  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:02:00.242  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:02:00.242  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:02:00.242  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:02:00.242  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4de0846 added. We now have 2 listener(s)
09-08 16:02:00.242  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:02:00.243  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-08 16:02:00.245  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:00.257  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:02:00.262  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:00.263  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:02:00.264  3865  3911 D executeNativeTests: Running unit tests
09-08 16:02:00.266  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:00.269  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:00.360  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 16:02:00.360  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 added. We now have 3 listener(s)
,09-08 16:02:00.361  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:02:00.361  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:02:00.361  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:02:00.362  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:02:00.362  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd added. We now have 3 listener(s)
09-08 16:02:00.362  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:02:00.363  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:02:00.368  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:00.386  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:02:00.389  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:00.390  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:02:00.392  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-08 16:02:00.394  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 16:02:00.394  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 16:02:00.394  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:02:00.394  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:00.396  3865  3911 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-08 16:02:00.397  3865  3911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-08 16:02:00.397  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,09-08 16:02:00.397  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:02:00.397  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:02:00.397  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:02:00.397  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:00.398  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:00.398  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:00.398  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:00.399  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:00.399  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:00.399  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:02:00.399  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-08 16:02:00.399  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 removed from the list
09-08 16:02:00.399  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:00.399  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd removed from the list
09-08 16:02:00.399  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:00.399  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:00.400  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:00.401  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:00.402  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:00.402  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:00.402  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:00.402  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:00.405  3865  3911 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,09-08 16:02:00.405  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:00.406  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:00.406  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:00.406  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:02:00.407  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:00.407  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:00.407  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:00.407  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:00.407  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:00.407  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:00.407  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:00.407  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:00.407  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:00.407  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:00.409  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:00.409  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:00.409  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:00.409  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:00.415  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 16:02:00.415  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-08 16:02:00.415  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 16:02:00.416  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-08 16:02:00.417  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 16:02:00.418  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-08 16:02:00.418  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 16:02:00.418  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:00.418  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:00.418  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:00.418  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:00.418  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:00.418  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:00.418  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:00.418  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:00.418  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:00.418  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:00.418  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:00.418  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:00.419  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:00.419  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:00.420  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:00.420  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:00.420  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:00.420  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:00.421  3865  3911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 16:02:00.422  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:00.431  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:02:00.435  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:00.436  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:02:00.437  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 16:02:00.438  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 16:02:00.439  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:00.440  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 16:02:00.441  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:02:00.442  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 16:02:00.442  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:00.452  3865  3911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 16:02:00.452  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 16:02:00.462  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:02:00.464  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 16:02:00.464  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:02:00.468  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,09-08 16:02:00.471  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,09-08 16:02:00.471  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 16:02:00.471  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:02:00.472  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 16:02:00.473  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:02:00.480  2665  2679 D BtGatt.GattService: registerClient() - UUID=1043c985-f9d4-44c8-8750-f10f71bc0285
,09-08 16:02:00.482  2665  2698 D BtGatt.GattService: onClientRegistered() - UUID=1043c985-f9d4-44c8-8750-f10f71bc0285, clientIf=5
,09-08 16:02:00.483  3865  3875 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 16:02:00.484  2665  2677 D BtGatt.GattService: start scan with filters
,09-08 16:02:00.487  2665  2701 D BtGatt.ScanManager: handling starting scan
,09-08 16:02:00.488  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 16:02:00.489  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 16:02:00.489  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 16:02:00.489  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 16:02:00.490  2665  2701 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:00.494  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:02:00.496  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:02:00.497  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 16:02:00.498  2665  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 16:02:00.498  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:00.498  2665  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 16:02:00.500  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:02:00.503  3865  3911 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 16:02:00.507  2665  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 16:02:00.507  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:00.508  2665  2701 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 16:02:00.508  2665  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 16:02:00.519  2665  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 16:02:00.519  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:00.531  2665  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 16:02:00.531  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:00.998  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 16:02:00.999  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:02:00.999  3865  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:02:02.041  2665  2665 D BtGatt.ScanManager: awakened up at time 339603
,09-08 16:02:02.043  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:02.101  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,09-08 16:02:02.101  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:02.102  2665  2698 D BtGatt.GattService: current time is 339664021216
,09-08 16:02:02.104  2665  2698 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -79, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -79, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 107, 58, 19, -9, 93, -60, 1, 0, -91, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 71, -122, -77, 84, 69, -12, 1, -128, -80, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -84, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 37, -47, 14, -113, 116, -46, 1, -128, -94, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -78, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 107, 58, 19, -9, 93, -60, 1, 0, -91, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 16:02:02.108  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,09-08 16:02:02.109  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:02:02.110  2665  2698 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 16:02:02.110  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:02:02.110  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 16:02:02.111  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 16:02:02.111  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:02:02.112  2665  2698 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 16:02:03.606  2665  2665 D BtGatt.ScanManager: awakened up at time 341168
,09-08 16:02:03.609  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:03.676  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
,09-08 16:02:03.676  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:03.677  2665  2698 D BtGatt.GattService: current time is 341238949817
,09-08 16:02:03.679  2665  2698 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -86, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, -46, -4, -117, 6, 105, -37, 1, -128, -88, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -89, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -85, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -79, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -86, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 107, 58, 19, -9, 93, -60, 1, 0, -86, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 16:02:03.680  2665  2698 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 16:02:03.682  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:02:03.683  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 16:02:03.685  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,09-08 16:02:03.686  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 16:02:03.688  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 16:02:03.689  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 16:02:03.690  2665  2698 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
,09-08 16:02:05.169  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:02:05.180  2665  2665 D BtGatt.ScanManager: awakened up at time 342741
,09-08 16:02:05.183  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:05.192  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:02:05.198  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:02:05.213  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
,09-08 16:02:05.214  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:05.214  2665  2698 D BtGatt.GattService: current time is 342776162240
09-08 16:02:05.214  2665  2698 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -85, 21, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, -46, -4, -117, 6, 105, -37, 1, -128, -88, 29, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -90, 28, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -79, 25, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 16:02:05.214  2665  2698 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 16:02:05.215  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:02:05.215  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:02:05.215  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:02:05.229  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,09-08 16:02:05.229  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
09-08 16:02:05.229  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:02:05.229  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:02:05.244  1527  1538 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
09-08 16:02:05.244  1527  1538 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
09-08 16:02:05.244  1527  1538 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
09-08 16:02:05.244  1527  1538 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
09-08 16:02:05.244  1527  1538 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
09-08 16:02:05.244  1527  1538 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
09-08 16:02:05.244  1527  1538 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 16:02:05.249  3512  3541 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
09-08 16:02:05.249  3512  3541 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
09-08 16:02:05.249  3512  3541 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
09-08 16:02:05.249  3512  3541 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
09-08 16:02:05.249  3512  3541 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
09-08 16:02:05.249  3512  3541 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
09-08 16:02:05.249  3512  3541 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,09-08 16:02:05.510  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:05.511  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:02:05.514  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 16:02:05.514  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:05.516  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:02:05.516  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:02:05.516  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 16:02:05.517  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:02:05.517  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 16:02:05.521  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 16:02:05.521  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 16:02:05.526  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:02:05.528  2665  2677 D BtGatt.GattService: stopScan() - queue size =1
,09-08 16:02:05.530  2665  2789 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:02:05.531  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:02:05.531  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 16:02:05.531  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 16:02:05.531  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 16:02:05.532  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:02:05.538  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:02:05.538  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 16:02:05.538  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:02:05.538  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:02:05.539  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:02:05.539  2665  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 16:02:05.540  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:05.540  2665  2701 D BtGatt.ScanManager: stopping BLe Batch
09-08 16:02:05.542  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:02:05.542  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:02:05.542  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:02:05.542  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:05.542  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:05.542  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:02:05.542  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:05.543  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:05.543  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:05.544  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:05.545  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:05.550  2665  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:02:05.550  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:05.550  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:05.557  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 16:02:05.557  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:06.043  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:02:10.548  3865  3911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,09-08 16:02:10.554  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
,09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:10.569  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:02:10.579  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:10.580  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:02:10.581  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 16:02:10.581  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 16:02:10.582  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 16:02:10.582  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:02:10.582  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 16:02:10.592  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:10.597  3865  3911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 16:02:10.597  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 16:02:10.598  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:10.609  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:02:10.611  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 16:02:10.611  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:02:10.620  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 16:02:10.620  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:02:10.620  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 16:02:10.623  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:02:10.629  2665  2679 D BtGatt.GattService: registerClient() - UUID=993e04fc-a82f-4423-bd84-47295943d8e1
,09-08 16:02:10.630  2665  2698 D BtGatt.GattService: onClientRegistered() - UUID=993e04fc-a82f-4423-bd84-47295943d8e1, clientIf=5
,09-08 16:02:10.632  3865  3876 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 16:02:10.633  2665  2677 D BtGatt.GattService: start scan with filters
,09-08 16:02:10.643  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 16:02:10.643  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,09-08 16:02:10.643  2665  2701 D BtGatt.ScanManager: handling starting scan
09-08 16:02:10.644  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 16:02:10.644  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 16:02:10.658  2665  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 16:02:10.658  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:02:10.659  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:10.659  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 16:02:10.659  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:02:10.659  2665  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:02:10.669  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:02:10.675  3865  3911 I io.jxcore.node.ConnectionHelper: start: OK
,09-08 16:02:10.677  2665  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 16:02:10.678  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.678  2665  2701 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 16:02:10.678  2665  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 16:02:10.680  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:10.680  3865  3911 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 16:02:10.680  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:02:10.680  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 16:02:10.680  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:10.681  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:02:10.681  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 16:02:10.681  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:02:10.681  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:02:10.681  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 16:02:10.682  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 16:02:10.682  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,09-08 16:02:10.683  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:02:10.684  2665  2679 D BtGatt.GattService: stopScan() - queue size =1
,09-08 16:02:10.687  2665  2677 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:02:10.687  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,09-08 16:02:10.688  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 16:02:10.688  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 16:02:10.688  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 16:02:10.689  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:02:10.689  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:02:10.690  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 16:02:10.690  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,09-08 16:02:10.690  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 16:02:10.690  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:02:10.691  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:02:10.691  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:02:10.692  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:02:10.692  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:10.692  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:10.692  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:02:10.692  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:10.692  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:10.692  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:10.692  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:10.692  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:10.693  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:10.693  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:10.695  2665  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 16:02:10.695  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.694  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:10.695  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:10.695  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:10.695  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:10.696  3865  3911 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-08 16:02:10.698  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:02:10.702  2665  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 16:02:10.702  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:10.703  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:02:10.705  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:10.705  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:02:10.705  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:02:10.705  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-08 16:02:10.705  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 16:02:10.705  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:02:10.705  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 16:02:10.709  3865  3911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 16:02:10.709  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 16:02:10.709  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:10.710  2665  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 16:02:10.710  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.710  2665  2701 D BtGatt.ScanManager: stopping BLe Batch
09-08 16:02:10.712  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:10.714  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-08 16:02:10.715  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 16:02:10.715  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-08 16:02:10.717  2665  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 16:02:10.717  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.717  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
09-08 16:02:10.718  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 16:02:10.719  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:02:10.719  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 16:02:10.719  3865  3911 D BluetoothAdapter: STATE_ON
09-08 16:02:10.722  2665  2808 D BtGatt.GattService: registerClient() - UUID=4b3cf3c9-f049-4da7-a078-b50feae74052
09-08 16:02:10.722  2665  2698 D BtGatt.GattService: onClientRegistered() - UUID=4b3cf3c9-f049-4da7-a078-b50feae74052, clientIf=5
09-08 16:02:10.722  3865  3875 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
09-08 16:02:10.723  2665  2789 D BtGatt.GattService: start scan with filters
09-08 16:02:10.724  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 16:02:10.724  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.726  2665  2701 D BtGatt.ScanManager: handling starting scan
09-08 16:02:10.727  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
09-08 16:02:10.727  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 16:02:10.727  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 16:02:10.727  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 16:02:10.731  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:02:10.731  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
09-08 16:02:10.731  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:02:10.733  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
09-08 16:02:10.734  2665  2698 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
09-08 16:02:10.734  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.734  2665  2701 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
09-08 16:02:10.735  3865  3911 I io.jxcore.node.ConnectionHelper: start: OK
09-08 16:02:10.740  2665  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 16:02:10.740  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:10.740  2665  2701 D BtGatt.ScanManager: Starting BLE batch scan
09-08 16:02:10.740  2665  2701 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
09-08 16:02:10.750  2665  2698 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
09-08 16:02:10.750  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:10.755  2665  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
09-08 16:02:10.755  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:11.232  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 16:02:11.232  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:02:11.233  3865  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:02:12.263  2665  2665 D BtGatt.ScanManager: awakened up at time 349825
,09-08 16:02:12.266  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:12.317  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,09-08 16:02:12.317  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:12.317  2665  2698 D BtGatt.GattService: current time is 349879815279
,09-08 16:02:12.319  2665  2698 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -89, 21, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, -46, -4, -117, 6, 105, -37, 1, -128, -81, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -81, 9, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -96, 13, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, 81, 34, 97, 112, -14, -5, 1, -128, -79, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -80, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -83, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:02:12.320  2665  2698 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 16:02:12.321  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:02:12.322  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,09-08 16:02:12.323  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-08 16:02:12.324  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,09-08 16:02:12.325  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 16:02:12.326  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:02:13.819  2665  2665 D BtGatt.ScanManager: awakened up at time 351381
,09-08 16:02:13.822  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:13.864  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,09-08 16:02:13.865  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:13.865  2665  2698 D BtGatt.GattService: current time is 351427549208
09-08 16:02:13.866  2665  2698 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -80, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -84, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -86, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -86, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -78, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -83, 10, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:02:13.867  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:02:13.868  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
09-08 16:02:13.869  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:02:13.869  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:02:13.870  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,09-08 16:02:13.871  2665  2698 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,09-08 16:02:15.368  2665  2665 D BtGatt.ScanManager: awakened up at time 352930
,09-08 16:02:15.370  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:15.383  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 16:02:15.384  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:15.736  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:15.736  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:15.737  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:02:15.737  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:15.737  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:02:15.738  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:02:15.738  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 16:02:15.738  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:02:15.739  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 16:02:15.739  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:02:15.739  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 16:02:15.743  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:02:15.745  2665  2789 D BtGatt.GattService: stopScan() - queue size =1
,09-08 16:02:15.748  2665  2677 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:02:15.749  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:02:15.749  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 16:02:15.749  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
09-08 16:02:15.750  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 16:02:15.750  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:02:15.754  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:02:15.755  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 16:02:15.755  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:02:15.755  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:02:15.756  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:02:15.760  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:02:15.761  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:02:15.761  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:02:15.762  2665  2698 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 16:02:15.762  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:15.762  2665  2701 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:02:15.775  2665  2698 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:02:15.775  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:02:15.776  2665  2701 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:02:15.792  2665  2698 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,09-08 16:02:15.792  2665  2698 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:02:16.262  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:02:16.262  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:16.262  3865  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:02:20.761  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:20.762  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:20.762  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:02:20.763  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:02:20.763  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.763  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:02:20.764  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:20.764  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.764  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.765  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.765  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.767  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.767  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.770  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:20.771  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:02:20.771  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.771  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:20.773  3865  3911 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,09-08 16:02:20.775  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:20.776  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:20.776  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:02:20.777  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.777  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.777  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.779  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:20.779  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:20.779  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.779  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.779  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.779  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.779  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.779  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.780  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:02:20.780  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:02:20.780  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:20.780  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:20.781  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,09-08 16:02:20.782  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:20.782  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:02:20.782  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:20.782  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.782  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:20.782  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.782  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:20.782  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:20.782  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:20.782  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:02:20.782  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:20.782  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.783  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.783  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.784  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:20.784  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:20.784  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:20.784  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.785  3865  3911 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-08 16:02:20.785  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:20.785  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:02:20.785  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:20.785  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.785  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.785  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.785  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:20.786  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.786  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.786  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.786  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.786  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.786  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.786  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.787  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:20.787  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:20.787  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.787  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.788  3865  3911 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,09-08 16:02:20.788  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:20.788  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:20.788  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:20.788  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:02:20.789  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.789  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.789  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:20.789  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:20.789  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.789  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.789  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:20.789  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.789  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.789  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.790  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:02:20.790  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:20.790  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.790  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.791  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 16:02:20.791  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 16:02:20.791  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:02:20.791  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 16:02:20.792  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:02:20.792  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:02:20.792  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-08 16:02:20.792  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,09-08 16:02:20.792  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-08 16:02:20.792  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:20.792  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:20.792  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:02:20.792  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.793  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.793  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.793  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:20.793  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:20.793  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.793  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.793  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.793  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.793  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.793  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.794  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:20.794  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:20.794  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:20.795  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.796  3865  3911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 16:02:20.796  3865  3911 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,09-08 16:02:20.796  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-08 16:02:20.800  3865  3911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 16:02:20.800  3865  3911 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-08 16:02:20.800  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
,09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710],
09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-08 16:02:20.801  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910],
09-08 16:02:20.802  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,09-08 16:02:20.802  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-08 16:02:20.802  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,09-08 16:02:20.802  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-08 16:02:20.802  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,09-08 16:02:20.802  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,09-08 16:02:20.802  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-08 16:02:20.803  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-08 16:02:20.803  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,09-08 16:02:20.803  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-08 16:02:20.803  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-08 16:02:20.804  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,09-08 16:02:20.805  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-08 16:02:20.805  3865  3911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-08 16:02:20.805  3865  3911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-08 16:02:20.805  3865  3911 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-08 16:02:20.806  3865  3911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-08 16:02:20.806  3865  3911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 16:02:20.806  3865  3911 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-08 16:02:20.806  3865  3911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 16:02:20.806  3865  3911 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,09-08 16:02:20.806  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-08 16:02:20.810  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-08 16:02:20.812  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-08 16:02:20.812  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-08 16:02:20.814  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-08 16:02:20.814  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-08 16:02:20.814  3865  3911 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55),
09-08 16:02:20.814  3865  3911 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-08 16:02:20.815  3865  3911 E io.jxcore.node.ConnectionHelper: connect: Callback is null
,09-08 16:02:20.815  3865  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 393)
09-08 16:02:20.815  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:20.815  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:20.815  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:02:20.816  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.816  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.816  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.816  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-08 16:02:20.817  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:20.817  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.817  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:20.817  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.817  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.817  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.817  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.817  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.817  3865  3916 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:02:20.819  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:02:20.819  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:20.819  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.819  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.819  3865  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 393
09-08 16:02:20.820  3865  3911 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,09-08 16:02:20.821  3865  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 393)
09-08 16:02:20.822  2665  2785 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
09-08 16:02:20.822  3865  3916 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 393)
09-08 16:02:20.822  3865  3917 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 393)
09-08 16:02:20.822  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:20.823  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:20.823  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:20.824  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.825  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.825  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.825  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:20.825  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.825  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.825  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.826  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:20.826  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.826  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.826  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.827  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:20.827  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:02:20.827  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.827  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.828  3865  3911 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-08 16:02:20.828  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:20.828  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:02:20.828  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:20.828  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.828  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.829  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.829  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:20.829  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.829  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.829  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.829  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.829  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:20.829  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.829  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.830  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:20.830  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:20.830  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.830  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:20.831  3865  3911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-08 16:02:20.831  3865  3911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-08 16:02:20.831  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 16:02:20.831  3865  3911 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-08 16:02:20.831  3865  3911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,09-08 16:02:20.831  3865  3911 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-08 16:02:20.831  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 16:02:20.831  3865  3911 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-08 16:02:20.832  3865  3911 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-08 16:02:20.832  3865  3911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-08 16:02:20.832  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,09-08 16:02:20.832  3865  3911 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-08 16:02:20.832  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:20.832  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:20.832  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:20.832  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:02:20.832  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.832  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.832  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:20.833  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.833  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:20.833  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.833  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.833  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.833  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:20.833  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.834  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:02:20.834  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:20.834  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.834  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.834  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:20.834  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:20.835  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:20.835  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:20.835  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:20.835  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:20.835  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:20.835  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:20.835  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:25.836  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:25.836  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.837  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:02:25.837  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:25.837  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.837  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:25.838  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:25.838  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:25.839  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:25.840  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:25.841  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.841  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.842  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:25.842  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.842  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.842  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:25.843  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.843  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.843  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.844  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.847  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:25.848  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:25.848  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.848  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:25.853  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,09-08 16:02:25.855  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:02:25.859  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...,
,09-08 16:02:25.862  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-08 16:02:25.863  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,09-08 16:02:25.865  3865  3865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,09-08 16:02:25.865  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,09-08 16:02:25.866  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,09-08 16:02:25.867  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:02:25.867  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-08 16:02:25.867  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 16:02:25.868  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 16:02:25.868  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.868  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-08 16:02:25.869  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:25.869  3865  3865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 16:02:25.869  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:25.869  3865  3918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:02:25.869  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-08 16:02:25.869  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:02:25.869  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 16:02:25.870  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.870  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.873  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:02:25.874  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.874  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:02:25.875  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:25.875  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:02:25.875  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:25.875  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:02:25.875  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:25.875  3865  3918 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 16:02:25.876  3865  3918 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 16:02:25.876  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:25.876  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:25.876  3865  3918 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-08 16:02:25.876  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.877  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:25.877  3865  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 16:02:25.877  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.877  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.878  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:25.878  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.878  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.878  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.879  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:25.881  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:25.882  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:25.882  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.882  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.885  3865  3911 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-08 16:02:25.886  3865  3911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,09-08 16:02:25.886  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-08 16:02:25.887  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:02:25.887  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-08 16:02:25.887  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:25.888  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:25.888  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:02:25.889  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:25.889  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.889  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.890  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:25.891  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.892  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:25.893  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:25.893  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:25.894  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:25.896  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.896  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:25.899  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:02:25.899  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:02:25.899  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
09-08 16:02:25.899  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:25.908  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:02:25.908  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:25.908  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:02:25.909  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:25.910  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.910  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.910  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
,09-08 16:02:25.910  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.911  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.911  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:25.911  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.911  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:25.912  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.912  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:25.914  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:02:25.914  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:02:25.914  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:25.915  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
,09-08 16:02:25.917  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:02:25.917  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:02:25.917  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:02:25.917  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:02:25.917  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:25.917  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.917  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@853564 not in the list
09-08 16:02:25.918  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.918  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.918  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:02:25.918  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.918  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.918  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:25.918  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:02:25.920  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:02:25.920  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:02:25.920  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:02:25.920  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e5463cd not in the list
09-08 16:02:25.922  3865  3911 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-08 16:02:25.922  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,09-08 16:02:25.923  3865  3911 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-08 16:02:25.923  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-08 16:02:25.923  3865  3911 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,09-08 16:02:25.923  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-08 16:02:25.927  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-08 16:02:25.927  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,09-08 16:02:25.929  3865  3911 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-08 16:02:25.929  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 16:02:25.929  3865  3911 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,09-08 16:02:25.930  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-08 16:02:25.930  3865  3911 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-08 16:02:25.930  3865  3911 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,09-08 16:02:25.931  3865  3911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-08 16:02:25.931  3865  3911 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,09-08 16:02:25.932  3865  3911 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-08 16:02:25.932  3865  3911 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-08 16:02:25.932  3865  3911 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-08 16:02:25.933  3865  3911 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,09-08 16:02:25.934  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:02:25.934  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9ee17e7 added. We now have 3 listener(s)
09-08 16:02:25.934  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:02:25.938  3865  3911 D BluetoothAdapter: enable(): BT is already enabled..!
,09-08 16:02:25.939   876  1931 D WifiService: setWifiEnabled: true pid=3865, uid=10000
09-08 16:02:25.939   876  1931 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:02:25.943  2665  2766 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,09-08 16:02:25.944  2665  2766 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
,09-08 16:02:26.376  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:02:30.950  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:02:30.951  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@952bf94 added. We now have 4 listener(s)
09-08 16:02:30.952  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:02:30.968  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:30.968  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@952bf94 removed from the list
09-08 16:02:30.969  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:30.969  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:30.969  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:30.972  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:02:30.972  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f12da3d added. We now have 4 listener(s)
,09-08 16:02:30.972  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:02:30.979  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:30.979  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f12da3d removed from the list
09-08 16:02:30.980  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:02:30.980  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:02:30.980  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:30.983  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:02:30.983  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b3b232 added. We now have 4 listener(s)
09-08 16:02:30.984  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:02:30.990   876  1998 D WifiService: setWifiEnabled: false pid=3865, uid=10000
09-08 16:02:30.990   876  1998 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:02:31.000  2665  2694 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 16:02:31.000  2665  2694 D BluetoothAdapterProperties: Setting state to 13
09-08 16:02:31.000  2665  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 16:02:31.002  2665  2694 D BluetoothAdapterProperties: onBluetoothDisable()
09-08 16:02:31.003  2665  2694 I BluetoothAdapterState: Entering PendingCommandState
09-08 16:02:31.006  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:02:31.011  2665  2698 D BluetoothAdapterProperties: Scan Mode:20
,09-08 16:02:31.011  2665  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 16:02:31.015  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:31.015  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:02:31.017  2665  2665 D HeadsetService: Received stop request...Stopping profile...
09-08 16:02:31.017  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.018  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 16:02:31.021   876  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 16:02:31.021   876  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 16:02:31.021   876  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 16:02:31.022   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:02:31.023   876   876 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:31.024  1363  2065 D BluetoothHeadset: Proxy object disconnected
,09-08 16:02:31.024  2665  2665 D A2dpService: Received stop request...Stopping profile...
09-08 16:02:31.024   876   876 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:31.024  1363  1363 D HeadsetProfile: Bluetooth service disconnected
,09-08 16:02:31.017  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:31.025  2665  2803 D A2dpStateMachine: Exit Disconnected: -1
09-08 16:02:31.029  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:02:31.030  1363  1363 D BluetoothA2dp: Proxy object disconnected
,09-08 16:02:31.030  2665  2665 V BluetoothAdapterState: isTurningOff()=true
,09-08 16:02:31.031  2665  2665 V BluetoothAdapterState: isTurningOn()=false
,09-08 16:02:31.031  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:31.031  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:31.025   876   876 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:31.032  1973  2122 D BluetoothHeadset: Proxy object disconnected
,09-08 16:02:31.033  2665  2665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,09-08 16:02:31.033  2665  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 16:02:31.033  2665  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:31.033  2665  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:31.033  2665  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 16:02:31.034  2665  2698 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 16:02:31.034  2665  2665 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 16:02:31.035  2665  2665 D HidService: Received stop request...Stopping profile...
09-08 16:02:31.035  2665  2665 D HidService: Stopping Bluetooth HidService
09-08 16:02:31.037  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-08 16:02:31.037  1363  1363 D HidProfile: Bluetooth service disconnected
09-08 16:02:31.038  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:31.038  2665  2665 D HealthService: Received stop request...Stopping profile...
09-08 16:02:31.035   876   876 D BluetoothA2dp: Proxy object disconnected
09-08 16:02:31.040  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:31.040  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:31.040  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false,
09-08 16:02:31.041  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:31.043  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.043  2665  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:31.043  2665  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,09-08 16:02:31.044  2665  2766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 16:02:31.044  2665  2766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 16:02:31.044  2665  2766 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 16:02:31.044  2665  2766 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,09-08 16:02:31.044  2665  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
09-08 16:02:31.045  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:31.045  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:31.045  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:31.045  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false,
09-08 16:02:31.046  2665  2665 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 16:02:31.046  2665  2698 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 16:02:31.046  2665  2665 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 16:02:31.047  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:31.047  2665  2665 V BluetoothAdapterState: isTurningOn()=false,
09-08 16:02:31.047  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:31.047  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:31.047  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
,09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:31.049  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:02:31.047  2665  2665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 16:02:31.049  2665  2698 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 16:02:31.049   876  1316 E native  : do suspend true
09-08 16:02:31.049  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:31.050  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:31.050  2665  2665 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 16:02:31.050  2665  2665 D PanService: Received stop request...Stopping profile...
09-08 16:02:31.052  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 16:02:31.052  1363  1363 D PanProfile: Bluetooth service disconnected
09-08 16:02:31.053  2665  2665 D BluetoothMapService: Received stop request...Stopping profile...
,09-08 16:02:31.053  2665  2665 D BluetoothMapService: stop()
,09-08 16:02:31.055  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:31.055  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:02:31.056  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.056  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:31.058  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.060  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:31.062  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.064  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.064   876  1935 D DhcpClient: Clearing IP address
09-08 16:02:31.065   373   874 D CommandListener: Setting iface cfg
09-08 16:02:31.067   373   874 D CommandListener: Clearing all IP addresses on wlan0
09-08 16:02:31.072  1527  2218 V NativeCrypto: Read error: ssl=0x9b6cec00: I/O error during system call, Connection timed out
,09-08 16:02:31.072   876  1949 D DhcpClient: Receive thread stopped
,09-08 16:02:31.074  1527  2218 V NativeCrypto: SSL shutdown failed: ssl=0x9b6cec00: I/O error during system call, Broken pipe
,09-08 16:02:31.077   876  1931 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
,09-08 16:02:31.077   876   889 I ActivityManager: Start proc 3925:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,09-08 16:02:31.077   876  1928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
,09-08 16:02:31.078  2665  2665 D BluetoothMapAppObserver: deinitObservers()
09-08 16:02:31.078  2665  2665 D BluetoothMapAppObserver: removeReceiver()
09-08 16:02:31.078   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-08 16:02:31.078   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
09-08 16:02:31.079   876  1316 D WifiStateMachine: Start Disconnecting Watchdog 1
09-08 16:02:31.079   876  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 16:02:31.079   876  1316 E native  : do suspend true
09-08 16:02:31.080  1363  1363 D BluetoothMap: Proxy object disconnected
09-08 16:02:31.080  1363  1363 D MapProfile: Bluetooth service disconnected
09-08 16:02:31.080  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:31.080  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:31.080  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:31.080  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:02:31.080  2665  2665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 16:02:31.081  2665  2665 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
09-08 16:02:31.082   876  1928 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
09-08 16:02:31.082   396   396 E Parcel  : Reading a NULL string not supported here.
09-08 16:02:31.084   876  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-08 16:02:31.087  2665  2665 D BluetoothMapService: MAP Service closeService in
09-08 16:02:31.087  2665  2665 D BluetoothMapMasInstance0: MAP Service shutdown
,09-08 16:02:31.087  2665  2665 D ObexServerSockets0: shutdown(block = true)
,09-08 16:02:31.088  2665  2811 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,09-08 16:02:31.089  2665  2665 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 16:02:31.089  2665  2812 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 16:02:31.089  2665  2785 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 16:02:31.089  2665  2665 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 16:02:31.090  2665  2665 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:31.090  2665  2665 V BluetoothAdapterState: isTurningOn()=false
,09-08 16:02:31.090  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:31.090  2665  2665 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:02:31.090  2665  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 16:02:31.090  2665  2694 D BluetoothAdapterProperties: Setting state to 15
,09-08 16:02:31.090  2665  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,09-08 16:02:31.091  2665  2694 I BluetoothAdapterState: Entering BleOnState
09-08 16:02:31.091  1363  1375 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 16:02:31.092  1363  2065 D BluetoothPan: onBluetoothStateChange on: false
09-08 16:02:31.092  2665  2665 D BluetoothMapService: cleanup()
09-08 16:02:31.092  2665  2665 D BluetoothMapService: MAP Service closeService in
09-08 16:02:31.093  1363  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:02:31.093   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:02:31.093  2665  2665 I BtOppRfcommListener: stopping Accept Thread
09-08 16:02:31.093  2665  3443 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 16:02:31.093  1363  1375 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 16:02:31.093  2665  3443 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 16:02:31.094  1363  2065 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 16:02:31.095   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 16:02:31.095  1363  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 16:02:31.097   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:02:31.097  1973  2122 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:02:31.097   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:02:31.097  2665  2694 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 16:02:31.097  2665  2694 D BluetoothAdapterProperties: Setting state to 16
09-08 16:02:31.097  2665  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
09-08 16:02:31.098  2665  2694 D BluetoothAdapterProperties: onBleDisable
09-08 16:02:31.099  2665  2694 I BluetoothAdapterState: Entering PendingCommandState
09-08 16:02:31.100  2665  2695 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 16:02:31.101  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:31.101  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:31.102  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.102  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:31.103  2665  2766 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 16:02:31.103  2665  2766 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:31.103  2665  2698 D BluetoothAdapterProperties: Scan Mode:20
09-08 16:02:31.106  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09,-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:31.106  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:31.106  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.106  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:31.108  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:31.108  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:31.109  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.109  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:31.110  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.111  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.112  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.121   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:02:31.130  3925  3925 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,09-08 16:02:31.139  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 16:02:31.141   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:02:31.141   373   874 D CommandListener: Clearing all IP addresses on wlan0
09-08 16:02:31.142   876  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-08 16:02:31.142   876  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:02:31.143   876  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:02:31.146  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:02:31.149   876   893 D Tethering: MasterInitialState.processMessage what=3
,09-08 16:02:31.152  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.153  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.154  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:31.155  3389  3389 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8c643c6 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
09-08 16:02:31.160   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7e44c3d:true
09-08 16:02:31.163   876  1997 I ActivityManager: Start proc 3943:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
09-08 16:02:31.165   876  1316 D WifiConfigStore: Retrieve network priorities after PNO.
09-08 16:02:31.167  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:31.167  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:31.168  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.168  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:31.168  2188  2353 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-08 16:02:31.169  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:31.169  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:31.170  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is dis,abled - will return stored value
09-08 16:02:31.170  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:31.170   876  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-08 16:02:31.171  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:31.171  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:31.172  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:31.172  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:02:31.182  3925  3925 D LocalBluetoothProfileManager: Adding local MAP profile
,09-08 16:02:31.184  3925  3925 D BluetoothMap: Create BluetoothMap proxy object
,09-08 16:02:31.191  3925  3925 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,09-08 16:02:31.204  3943  3943 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,09-08 16:02:31.206  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:02:31.207   373   874 E Netd    : netlink response contains error (No such file or directory)
,09-08 16:02:31.207   876  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
09-08 16:02:31.207   876  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,09-08 16:02:31.212   876  1931 I ActivityManager: Killing 3066:com.google.android.talk/u0a61 (adj 15): empty #17
,09-08 16:02:31.303  2665  2698 I bt_hci  : shut_down
,09-08 16:02:31.304  2665  2702 D bt_hwcfg: hw_epilog_process
,09-08 16:02:31.305  2665  2702 I bt_vendor: low_power_mode_cb
,09-08 16:02:31.327  2665  2702 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,09-08 16:02:31.328  2665  2702 I bt_vendor: epilog_cb
09-08 16:02:31.328  2665  2702 I bt_hci  : epilog_finished_callback
,09-08 16:02:31.334  2665  2698 I bt_hci_h4: hal_close
,09-08 16:02:31.335  2665  2698 I bt_userial_vendor: device fd = 51 close
,09-08 16:02:31.405  3943  3943 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 16:02:31.405  3943  3943 D StrictMode: 	,at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:02:31.405  3943  3943 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.Instr,umentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:02:31.405  3943  3943 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,09-08 16:02:31.405  3943  3943 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.k.a(PG:2107)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:02:31.405  3943  3943 D StrictMode: StrictMode policy violation; ~duration=95 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.,java:290)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.k.d(PG:1187)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.k.c(PG:18147)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.k.d(PG:583)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.v.a(PG:1161)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.y.a(PG:2188)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:170)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.r.e.b(PG:15188)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:02:31.405  3943  3943 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09,-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:02:31.405  3943  3943 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.File.doAccess(File.java:281)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.io.File.exists(File.java:361)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.405  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:02:31.406  3943  3943 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at java.io.File.lastModified(File.java:569)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:02:31.406  3943  3943 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:02:31.409  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 16:02:31.416  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 16:02:31.443   876  1998 I ActivityManager: Start proc 3976:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
09-08 16:02:31.449  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:02:31.451   876  1931 I ActivityManager: Killing 3565:com.google.process.gapps/u0a99 (adj 15): empty #17
,09-08 16:02:31.528  2665  2695 D bt_stack_manager: event_shut_down_stack finished.
,09-08 16:02:31.529  2665  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 16:02:31.533  2665  2665 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 16:02:31.533  2665  2694 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
09-08 16:02:31.534  2665  2665 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 16:02:31.534  2665  2665 D BtGatt.GattService: stop()
09-08 16:02:31.534  2665  2665 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 16:02:31.536  2665  2665 V BluetoothAdapterState: isTurningOff()=false
09-08 16:02:31.536  2665  2665 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:31.536  2665  2665 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:31.536  2665  2665 V BluetoothAdapterState: isBleTurningOff()=true
,09-08 16:02:31.537  2665  2694 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
09-08 16:02:31.537  2665  2694 D BluetoothAdapterProperties: Setting state to 10
09-08 16:02:31.538  2665  2694 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 16:02:31.539  2665  2694 I BluetoothAdapterState: Entering OffState
09-08 16:02:31.539   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,09-08 16:02:31.555  3976  3976 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,09-08 16:02:31.559  2665  2665 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 16:02:31.560  2665  2665 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-08 16:02:31.560  2665  2695 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
09-08 16:02:31.562  2665  2695 D bt_stack_manager: event_clean_up_stack finished.
,09-08 16:02:31.562  2665  2665 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 16:02:31.564  2665  2665 I art     : System.exit called, status: 0
09-08 16:02:31.564  2665  2665 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 16:02:31.617   876  3160 I ActivityManager: Process com.android.bluetooth (pid 2665) has died
,09-08 16:02:31.805  3976  3997 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,09-08 16:02:31.805  3976  3997 I Babel_SMS: MmsConfig.loadMmsSettings
,09-08 16:02:31.810  3976  3997 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 16:02:31.810  3976  3997 I Babel_SMS: MmsConfig.loadFromDatabase
,09-08 16:02:31.862  3976  3997 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,09-08 16:02:31.863  3976  3997 I Babel_SMS: MmsConfig.loadFromResources
,09-08 16:02:31.864  3976  3997 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
09-08 16:02:31.865  3976  3997 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,09-08 16:02:31.924  3976  3976 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 16:02:31.927  3976  3976 I Babel_Crash: startup - clean
,09-08 16:02:31.949  3976  3976 I Babel_telephony: TeleModule.launchCompleted
,09-08 16:02:31.960   876  3160 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 16:02:31.976  3976  3976 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,09-08 16:02:31.984  3976  3976 W Babel   : BAM#gBA: invalid account id: -1
,09-08 16:02:31.984  3976  3976 W Babel   : BAM#gBA: invalid account id: -1
09-08 16:02:31.984  3976  3976 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,09-08 16:02:31.995  3976  4002 I Babel   : deleted: false for 0
,09-08 16:02:31.996   876  1997 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,09-08 16:02:32.023  1766  1766 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 16:02:32.045  1766  1766 D SystemUpdateService: onCreate
,09-08 16:02:32.052  1766  1766 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 16:02:32.065  3943  3966 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,09-08 16:02:32.075  1766  4004 I SystemUpdateService: active receiver: enabled
,09-08 16:02:32.080  1766  4004 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 16:02:32.082  1766  4004 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 16:02:32.082  1766  4004 I SystemUpdateService: now status is 0 (complete)
09-08 16:02:32.082  1766  4004 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 16:02:32.082  1766  4004 I SystemUpdateService: file has been verified
09-08 16:02:32.083  1766  4004 I SystemUpdateService: OTA package size = 12249756
,09-08 16:02:32.088  1766  1766 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-08 16:02:32.090  1766  2430 I iu.UploadsManager: num queued entries: 0
,09-08 16:02:32.090  1766  2430 I iu.UploadsManager: num updated entries: 0
,09-08 16:02:32.092  1766  2430 I iu.SyncManager: NEXT; no task
,09-08 16:02:32.094  1766  4004 I SystemUpdateService: showing system update notification
,09-08 16:02:32.097  3976  3976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 16:02:32.105  1766  1766 D SystemUpdateService: onDestroy
,09-08 16:02:32.112  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 16:02:32.114  1766  1766 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 16:02:32.130   876   887 I ActivityManager: Start proc 4006:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,09-08 16:02:32.176  4006  4006 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,09-08 16:02:32.185  4006  4006 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:02:32.187  3976  3976 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,09-08 16:02:32.195  3976  3976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 16:02:32.197  3976  3976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 16:02:32.215  3976  3976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
09-08 16:02:32.215  4006  4006 D SprintDMHelper: simOperator: 
09-08 16:02:32.215  4006  4006 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 16:02:32.233  3976  3976 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,09-08 16:02:32.236   876  1997 I ActivityManager: Start proc 4018:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,09-08 16:02:32.246   876  3160 I ActivityManager: Killing 3389:com.google.android.music:main/u0a66 (adj 15): empty #17
,09-08 16:02:32.269   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b2a5751:true
,09-08 16:02:32.379  3976  3976 I vclib   : onServiceConnected
,09-08 16:02:32.483   876  3160 I ActivityManager: Start proc 4033:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
09-08 16:02:32.486  3976  4032 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,09-08 16:02:32.490   876  1931 I ActivityManager: Killing 3458:com.android.providers.calendar/u0a3 (adj 15): empty #17
,09-08 16:02:32.552  4033  4033 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,09-08 16:02:32.611  4033  4033 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-08 16:02:32.611  4033  4033 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-08 16:02:32.611  4033  4033 I GAv4    :   adb logcat -s GAv4
,09-08 16:02:32.635  4033  4033 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-08 16:02:32.642  4033  4033 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-08 16:02:32.666  4033  4051 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-08 16:02:32.778  4033  4033 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,09-08 16:02:32.813  4033  4033 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,09-08 16:02:32.826  4033  4033 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 381-388)
,09-08 16:02:32.829  4033  4033 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-08 16:02:32.839  4033  4033 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {d8d2a76}
,09-08 16:02:32.840  4033  4033 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-08 16:02:32.840  4033  4033 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-08 16:02:32.850  4033  4033 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-08 16:02:32.851  4033  4033 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-08 16:02:32.870  4033  4033 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-08 16:02:32.886  4033  4033 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 16:02:32.886  4033  4033 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-08 16:02:32.886  4033  4033 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
09-08 16:02:32.886  4033  4033 I Adreno  : Build Date                       : 10/20/15
09-08 16:02:32.886  4033  4033 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
09-08 16:02:32.886  4033  4033 I Adreno  : Local Branch                     : M14
09-08 16:02:32.886  4033  4033 I Adreno  : Remote Branch                    : 
09-08 16:02:32.886  4033  4033 I Adreno  : Remote Branch                    : 
09-08 16:02:32.886  4033  4033 I Adreno  : Reconstruct Branch               : 
,09-08 16:02:32.955  4033  4033 I NSApplication: Starting up...
,09-08 16:02:32.977  4033  4079 W AudioManagerAndroid: Requires BLUETOOTH permission
,09-08 16:02:32.979   876  1931 I ActivityManager: Start proc 4084:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,09-08 16:02:32.983   876  1931 I ActivityManager: Killing 3495:android.process.acore/u0a5 (adj 15): empty #17
,09-08 16:02:33.092  4084  4084 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,09-08 16:02:33.272   876  1384 I ActivityManager: Killing 3650:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,09-08 16:02:33.366   876  1384 I ActivityManager: Start proc 4098:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,09-08 16:02:33.453  4098  4098 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,09-08 16:02:33.511  4098  4098 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,09-08 16:02:33.523   876  1544 I ActivityManager: Killing 3665:com.android.musicfx/u0a18 (adj 15): empty #17
,09-08 16:02:36.035   876  1931 D WifiService: setWifiEnabled: true pid=3865, uid=10000
,09-08 16:02:36.036   876  1931 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:02:36.062  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:36.062  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:36.062  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:36.062  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:36.063   876  1316 D WifiConfigStore: Loading config and enabling all networks 
09-08 16:02:36.064  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:36.064  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:36.064  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:36.064  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:02:36.065  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:36.065  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:36.066  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:36.066  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null,
,09-08 16:02:36.079   876  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-08 16:02:36.080   876  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 16:02:36.081   876  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-08 16:02:36.082   876  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 16:02:36.082   876  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,09-08 16:02:36.082   876  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
09-08 16:02:36.082   876  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,09-08 16:02:36.107   373   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,09-08 16:02:36.107   876  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
09-08 16:02:36.108   373   874 D CommandListener: Setting iface cfg
,09-08 16:02:36.109   876  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '134 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 134 Failed to set address (No such device)'
,09-08 16:02:36.109   876  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 16:02:36.117   876  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 16:02:36.117   876  1316 E native  : do suspend true
09-08 16:02:36.117   876  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,09-08 16:02:36.140   876  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:02:36.934   876  3160 I ActivityManager: Killing 2250:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,09-08 16:02:37.407   876  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:02:37.478   876  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=6.56 rxSuccessRate=12.56 delta 1000 -> 994
,09-08 16:02:37.479   876  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
09-08 16:02:37.480   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:02:37.498   876  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 16:02:37.567   876  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 16:02:37.570  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 16:02:37.999  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 16:02:38.070  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 16:02:38.071  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 16:02:38.076   876  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:02:38.086   876  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 16:02:38.086   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:02:38.087   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 16:02:38.103   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:02:38.116   373   874 D CommandListener: Setting iface cfg
,09-08 16:02:38.117   876  1316 D WifiStateMachine: Start Dhcp Watchdog 2
,09-08 16:02:38.125   876  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 16:02:38.158   876  4133 D DhcpClient: Receive thread started
,09-08 16:02:38.242   876  1316 E native  : do suspend false
,09-08 16:02:38.265   876  1935 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 16:02:38.287   876  4133 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172448, domain null
,09-08 16:02:38.289   876  1935 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172448 seconds
,09-08 16:02:38.294   876  1935 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 16:02:38.313   876  4133 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 16:02:38.317   876  1935 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 16:02:38.323   373   874 D CommandListener: Setting iface cfg
,09-08 16:02:38.334   876  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 16:02:38.337   876  1935 D DhcpClient: Scheduling renewal in 86399s
09-08 16:02:38.337   876  1316 E native  : do suspend true
,09-08 16:02:38.357   876  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 16:02:38.361   876  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 16:02:38.363   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,09-08 16:02:38.365   876  1318 D ConnectivityService: Adding iface wlan0 to network 101
,09-08 16:02:38.378   876  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 16:02:38.450   876  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
09-08 16:02:38.450   876  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
09-08 16:02:38.452   876  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,09-08 16:02:38.453   876  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
09-08 16:02:38.454   876  1318 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,09-08 16:02:38.465   876  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,09-08 16:02:38.472   876  1318 D ConnectivityService: scheduleUnvalidatedPrompt 101
,09-08 16:02:38.472   876  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
09-08 16:02:38.472   876  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
09-08 16:02:38.472   876  1318 D ConnectivityService:    accepting network in place of null
09-08 16:02:38.472   876  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
09-08 16:02:38.473   876  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 16:02:38.473   876  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 16:02:38.481   876  4130 D NetlinkSocketObserver: NeighborEvent{elapsedMs=376043, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:02:38.505   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:02:38.552   876  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 16:02:38.559   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:02:38.570   876  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,09-08 16:02:38.571   876  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:02:38.579   876  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,09-08 16:02:38.580   876   893 D Tethering: MasterInitialState.processMessage what=3
,09-08 16:02:38.595  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:38.595  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:02:38.595  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:38.595  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:38.598  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:38.599  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:02:38.599  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:38.599  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:38.603  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:02:38.603  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-08 16:02:38.603  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:38.603  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:02:38.611  1766  1766 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 16:02:38.618  1766  1766 D SystemUpdateService: onCreate
09-08 16:02:38.620   876  4129 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 14:02:38 GMT], X-Android-Received-Millis=[1473343358620], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473343358591]}
09-08 16:02:38.622   876  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 16:02:38.622   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
09-08 16:02:38.622   876  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
09-08 16:02:38.623  1766  1766 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-08 16:02:38.624   876  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 16:02:38.648  1766  4144 I SystemUpdateService: active receiver: enabled
,09-08 16:02:38.653  1766  1766 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 16:02:38.656  1766  2430 I iu.UploadsManager: num queued entries: 0
,09-08 16:02:38.656  1766  2430 I iu.UploadsManager: num updated entries: 0
,09-08 16:02:38.665  1766  4144 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 16:02:38.668  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 16:02:38.669  1766  1766 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 16:02:38.673  4006  4006 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:02:38.675  1766  4147 I MDM     : [177] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,09-08 16:02:38.675  1766  4147 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 16:02:38.677  1766  4147 V GoogleAuthProtoRequest: [177] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 16:02:38.684  4006  4006 D SprintDMHelper: simOperator: 
,09-08 16:02:38.684  4006  4006 D SprintDMReceiver: Not Sprint UICC, don't do anything.
09-08 16:02:38.684  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:02:38.686  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:02:38.690  1766  2430 I iu.SyncManager: NEXT; no task
,09-08 16:02:38.689  1766  4144 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 16:02:38.690  1766  4144 I SystemUpdateService: now status is 0 (complete)
09-08 16:02:38.690  1766  4144 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 16:02:38.690  1766  4144 I SystemUpdateService: file has been verified
,09-08 16:02:38.690  1766  4144 I SystemUpdateService: OTA package size = 12249756
,09-08 16:02:38.717  1766  4144 I SystemUpdateService: showing system update notification
,09-08 16:02:38.777  1766  1766 D SystemUpdateService: onDestroy
,09-08 16:02:38.794  1527  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 16:02:38.794  1527  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 16:02:38.794  1527  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 16:02:38.794  1527  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:02:38.814  1766  4147 E MDM     : [177] SitrepService.a: Error sending sitrep.
,09-08 16:02:38.846  3976  4151 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 16:02:39.569   876  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,09-08 16:02:41.069   876  1544 D WifiService: setWifiEnabled: false pid=3865, uid=10000
09-08 16:02:41.069   876  1544 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:02:41.101  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,09-08 16:02:41.106   876  1316 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,09-08 16:02:41.106   876  1316 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,09-08 16:02:41.106   876  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
09-08 16:02:41.107   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:02:41.116   876  1316 E native  : do suspend true
,09-08 16:02:41.127   876  1935 D DhcpClient: Clearing IP address
09-08 16:02:41.127   373   874 D CommandListener: Clearing all IP addresses on wlan0
,09-08 16:02:41.130   373   874 D CommandListener: Setting iface cfg
,09-08 16:02:41.136   876  4133 D DhcpClient: Receive thread stopped
,09-08 16:02:41.143  1527  4155 V NativeCrypto: Read error: ssl=0x9b27b400: I/O error during system call, Connection timed out
,09-08 16:02:41.146  1527  4155 V NativeCrypto: SSL shutdown failed: ssl=0x9b27b400: I/O error during system call, Broken pipe
,09-08 16:02:41.148   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,09-08 16:02:41.148   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,09-08 16:02:41.153   876  1316 D WifiStateMachine: Start Disconnecting Watchdog 2
09-08 16:02:41.153   396   396 E Parcel  : Reading a NULL string not supported here.
09-08 16:02:41.156   876  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 16:02:41.156   876  1316 E native  : do suspend true
,09-08 16:02:41.161   876  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,09-08 16:02:41.190   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:02:41.214   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:02:41.216   876  1318 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
09-08 16:02:41.216   876  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
09-08 16:02:41.216   373   874 D CommandListener: Clearing all IP addresses on wlan0
,09-08 16:02:41.220   876   893 D Tethering: MasterInitialState.processMessage what=3
,09-08 16:02:41.223  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:41.226  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:41.226  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.227  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:41.228  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:41.228  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:41.228  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.228  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:41.229  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:41.229  3865  3865 V io.jxcore.node.ConnectivityMonitor:  ,   - active network type is Wi-Fi: false
09-08 16:02:41.229  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.229  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:41.239  1766  1766 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
09-08 16:02:41.242  1766  1766 D SystemUpdateService: onCreate
09-08 16:02:41.245  1766  1766 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
09-08 16:02:41.253  1766  4166 I SystemUpdateService: active receiver: enabled
09-08 16:02:41.254  1766  1766 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
09-08 16:02:41.256  1766  2430 I iu.UploadsManager: num queued entries: 0
09-08 16:02:41.256  1766  2430 I iu.UploadsManager: num updated entries: 0
09-08 16:02:41.262  1766  4166 I SystemUpdateService: Already downloaded, skipping offpeak checks.
09-08 16:02:41.263  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
09-08 16:02:41.264  1766  1766 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
09-08 16:02:41.266  4006  4006 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-08 16:02:41.270  4006  4006 D SprintDMHelper: simOperator: 
09-08 16:02:41.270  4006  4006 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 16:02:41.297   373   874 E Netd    : netlink response contains error (No such file or directory)
,09-08 16:02:41.298   876  1318 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,09-08 16:02:41.299   876  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:02:41.313  1766  2430 I iu.SyncManager: NEXT; no task
,09-08 16:02:41.315   876  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:02:41.317  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:41.318  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:02:41.318  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.318  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:41.319  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:41.319  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:41.319  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.319  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:02:41.321  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:41.321  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:41.321  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:41.321  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:41.324  2188  2353 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-08 16:02:41.328   876  1316 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,09-08 16:02:41.330  3976  4170 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,09-08 16:02:41.337  1766  4166 I SystemUpdateService: network: null; metered: false; mobile allowed: true
09-08 16:02:41.337  1766  4166 I SystemUpdateService: now status is 0 (complete)
09-08 16:02:41.337  1766  4166 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,09-08 16:02:41.337  1766  4166 I SystemUpdateService: file has been verified
09-08 16:02:41.339  1766  4166 I SystemUpdateService: OTA package size = 12249756
,09-08 16:02:41.347  1766  4166 I SystemUpdateService: showing system update notification
,09-08 16:02:41.355  1766  1766 D SystemUpdateService: onDestroy
,09-08 16:02:44.581  1910  1948 I Keyboard.Facilitator.LanguageModelFlusher: run()
,09-08 16:02:44.582  1910  1948 I Keyboard.Facilitator: flushDynamicLanguageModels()
,09-08 16:02:44.613  1527  1527 I ConfigService: onCreate
,09-08 16:02:46.135   876   893 I ActivityManager: Start proc 4176:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 16:02:46.217  4176  4176 D AdapterServiceConfig: Adding HeadsetService
,09-08 16:02:46.217  4176  4176 D AdapterServiceConfig: Adding A2dpService
09-08 16:02:46.217  4176  4176 D AdapterServiceConfig: Adding HidService
09-08 16:02:46.217  4176  4176 D AdapterServiceConfig: Adding HealthService
09-08 16:02:46.217  4176  4176 D AdapterServiceConfig: Adding PanService
,09-08 16:02:46.218  4176  4176 D AdapterServiceConfig: Adding GattService
09-08 16:02:46.218  4176  4176 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 16:02:46.230  4176  4176 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 16:02:46.230   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d4d97f1:true
,09-08 16:02:46.236  4176  4176 I bt_bluedroid: init
,09-08 16:02:46.236  4176  4188 I BluetoothAdapterState: Entering OffState
,09-08 16:02:46.241  4176  4189 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 16:02:46.242  4176  4189 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,09-08 16:02:46.242  4176  4189 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
09-08 16:02:46.243  4176  4189 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,09-08 16:02:46.244  4176  4176 I bt_bluedroid: get_profile_interface socket
,09-08 16:02:46.246  4176  4176 I bt_bluedroid: get_profile_interface sdp
,09-08 16:02:46.250  4176  4192 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 16:02:46.251  4176  4192 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 16:02:46.252  4176  4187 I bt_bluedroid: config_hci_snoop_log
,09-08 16:02:46.256   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 16:02:46.265  4176  4188 D BluetoothAdapterState: Current state: OFF, message: 0
,09-08 16:02:46.265  4176  4188 D BluetoothAdapterProperties: Setting state to 14
,09-08 16:02:46.266  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,09-08 16:02:46.270  4176  4188 D BluetoothBondStateMachine: make
,09-08 16:02:46.278  4176  4193 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 16:02:46.283  4176  4188 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:02:46.286  4176  4176 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 16:02:46.294  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:46.296  4176  4176 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 16:02:46.297  4176  4176 D BtGatt.GattService: Received start request. Starting profile...
,09-08 16:02:46.298  4176  4176 D BtGatt.GattService: start()
09-08 16:02:46.298  4176  4176 I bt_bluedroid: get_profile_interface gatt
,09-08 16:02:46.300  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:46.300  4176  4176 D BtGatt.AdvertiseManager: advertise manager created
,09-08 16:02:46.310  4176  4176 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:02:46.310  4176  4176 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:46.311  4176  4176 V BluetoothAdapterState: isBleTurningOn()=true
09-08 16:02:46.311  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:02:46.312  4176  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,09-08 16:02:46.313  4176  4188 I bt_bluedroid: enable
09-08 16:02:46.313  4176  4189 D bt_stack_manager: event_start_up_stack is bringing up the stack.
09-08 16:02:46.314  4176  4189 I bt_hci  : start_up
,09-08 16:02:46.333  4176  4189 I bt_vendor: alloc value 0xb3a08189
,09-08 16:02:46.334  4176  4189 I bt_vendor: init
,09-08 16:02:46.334  4176  4189 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 16:02:46.334  4176  4189 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 16:02:46.444  4176  4189 D bt_hci  : start_up starting async portion
,09-08 16:02:46.444  4176  4196 I bt_hci  : event_finish_startup
,09-08 16:02:46.445  4176  4196 I bt_hci_h4: hal_open
,09-08 16:02:46.447  4176  4196 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 16:02:46.458  4176  4196 I bt_userial_vendor: device fd = 51 open
,09-08 16:02:46.478   876  1318 D ConnectivityService: handlePromptUnvalidated 101
,09-08 16:02:46.485  4176  4196 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:02:46.517  4176  4196 D bt_hwcfg: Chipset BCM4354A2
09-08 16:02:46.517  4176  4196 D bt_hwcfg: Target name = [BCM4354A2]
,09-08 16:02:46.519  4176  4196 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 16:02:47.186  4176  4196 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 16:02:47.188  4176  4196 D bt_hwcfg: Settlement delay -- 100 ms
,09-08 16:02:47.188  4176  4196 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 16:02:47.305  4176  4196 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:02:47.306  4176  4196 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 16:02:47.335  4176  4196 I bt_hwcfg: vendor lib fwcfg completed
09-08 16:02:47.335  4176  4196 I bt_vendor: firmware callback
09-08 16:02:47.335  4176  4196 I bt_hci  : firmware_config_callback
,09-08 16:02:47.347  4176  4198 I bt_btu  : btu_task pending for preload complete event
09-08 16:02:47.347  4176  4198 I bt_btu_task: Bluetooth chip preload is complete
09-08 16:02:47.347  4176  4198 I bt_btu  : btu_task received preload complete event
,09-08 16:02:47.358  4176  4198 I         : BTE_InitTraceLevels -- TRC_HCI
09-08 16:02:47.359  4176  4198 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 16:02:47.359  4176  4198 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 16:02:47.359  4176  4198 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 16:02:47.359  4176  4198 I         : BTE_InitTraceLevels -- TRC_AVRC
09-08 16:02:47.360  4176  4198 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 16:02:47.360  4176  4198 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 16:02:47.360  4176  4198 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 16:02:47.360  4176  4198 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 16:02:47.361  4176  4198 I         : BTE_InitTraceLevels -- TRC_PAN
09-08 16:02:47.361  4176  4198 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 16:02:47.361  4176  4198 I         : BTE_InitTraceLevels -- TRC_GATT
,09-08 16:02:47.362  4176  4198 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 16:02:47.362  4176  4198 I         : BTE_InitTraceLevels -- TRC_BTAPP
09-08 16:02:47.362  4176  4198 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 16:02:47.500  4176  4198 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3985d9d
,09-08 16:02:47.500  4176  4198 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3985d9d 
,09-08 16:02:47.507  4176  4192 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,09-08 16:02:47.509  4176  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 16:02:47.511  4176  4192 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 16:02:47.516  4176  4192 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 16:02:47.520  4176  4192 D BluetoothAdapterProperties: Scan Mode:20
09-08 16:02:47.521  4176  4192 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 16:02:47.522  4176  4192 D bt_hci  : do_postload posting postload work item
09-08 16:02:47.522  4176  4196 I bt_hci  : event_postload
09-08 16:02:47.522  4176  4196 I bt_vendor: sco_config_cb
09-08 16:02:47.522  4176  4196 I bt_hci  : sco_config_callback postload finished.
,09-08 16:02:47.525  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:47.526  4176  4192 D bt_bte_conf: Device ID record 1 : primary
09-08 16:02:47.526  4176  4192 D bt_bte_conf:   vendorId            = 000f
09-08 16:02:47.526  4176  4192 D bt_bte_conf:   vendorIdSource      = 0001
09-08 16:02:47.526  4176  4192 D bt_bte_conf:   product             = 1200
09-08 16:02:47.527  4176  4192 D bt_bte_conf:   version             = 1436
09-08 16:02:47.527  4176  4192 D bt_bte_conf:   clientExecutableURL = 
09-08 16:02:47.527  4176  4192 D bt_bte_conf:   serviceDescription  = 
09-08 16:02:47.527  4176  4192 D bt_bte_conf:   documentationURL    = 
09-08 16:02:47.527  4176  4192 D bt_bte_conf: bte_load_did_conf no section named DID2.
09-08 16:02:47.528  4176  4189 D bt_stack_manager: event_start_up_stack finished
,09-08 16:02:47.529  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:47.529  4176  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 16:02:47.530  4176  4188 D BluetoothAdapterProperties: Setting state to 15
,09-08 16:02:47.530  4176  4196 I bt_vendor: low_power_mode_cb
09-08 16:02:47.530  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 16:02:47.531  4176  4188 I BluetoothAdapterState: Entering BleOnState
09-08 16:02:47.533  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:47.537  4176  4188 D BluetoothAdapterState: Current state: BLE ON, message: 1
,09-08 16:02:47.538  4176  4188 D BluetoothAdapterProperties: Setting state to 11
09-08 16:02:47.539  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 16:02:47.545  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:47.546  4176  4176 D HeadsetService: Received start request. Starting profile...
,09-08 16:02:47.554  4176  4176 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,09-08 16:02:47.555  4176  4176 D HeadsetStateMachine: make
,09-08 16:02:47.558  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:47.560  4176  4188 I BluetoothAdapterState: Entering PendingCommandState
09-08 16:02:47.560  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:47.562  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:47.566  4176  4176 D HeadsetStateMachine: max_hf_connections = 1
09-08 16:02:47.566  4176  4176 I bt_bluedroid: get_profile_interface handsfree
09-08 16:02:47.566  4176  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,09-08 16:02:47.566  4176  4192 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,09-08 16:02:47.569  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:47.570  4176  4176 D A2dpService: Received start request. Starting profile...
,09-08 16:02:47.571  4176  4176 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 16:02:47.571  4176  4176 I bt_bluedroid: get_profile_interface avrcp
,09-08 16:02:47.578  4176  4176 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 16:02:47.578  4176  4176 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 16:02:47.578  4176  4176 D A2dpStateMachine: make
,09-08 16:02:47.580  4176  4176 I bt_bluedroid: get_profile_interface a2dp
,09-08 16:02:47.580  4176  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 16:02:47.586  4176  4207 D A2dpStateMachine: Enter Disconnected: -2
,09-08 16:02:47.586  4176  4176 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 16:02:47.587  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:47.588  4176  4176 D HidService: Received start request. Starting profile...
09-08 16:02:47.589  3925  3925 D BluetoothInputDevice: Proxy object connected
,09-08 16:02:47.589  4176  4176 I bt_bluedroid: get_profile_interface hidhost
09-08 16:02:47.589  4176  4176 D HidService: setHidService(): set to: null
09-08 16:02:47.589  4176  4192 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39673e5
,09-08 16:02:47.589  4176  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 16:02:47.590  4176  4176 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 16:02:47.590  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
09-08 16:02:47.591  3925  3925 D HidProfile: Bluetooth service connected
09-08 16:02:47.591  4176  4176 D HealthService: Received start request. Starting profile...
,09-08 16:02:47.593  4176  4176 I bt_bluedroid: get_profile_interface health
09-08 16:02:47.593  4176  4176 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 16:02:47.594  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:47.595  4176  4176 D PanService: Received start request. Starting profile...
09-08 16:02:47.595  3925  3925 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 16:02:47.595  4176  4176 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 16:02:47.596  4176  4176 I bt_bluedroid: get_profile_interface pan
09-08 16:02:47.596  4176  4192 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
09-08 16:02:47.596  3925  3925 D PanProfile: Bluetooth service connected
,09-08 16:02:47.600  4176  4176 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:02:47.602  4176  4176 D BluetoothMapService: Received start request. Starting profile...
,09-08 16:02:47.602  3925  3925 D BluetoothMap: Proxy object connected
09-08 16:02:47.602  4176  4176 D BluetoothMapService: start()
09-08 16:02:47.602  3925  3925 D MapProfile: Bluetooth service connected
09-08 16:02:47.603  3925  3925 D BluetoothMap: getConnectedDevices()
09-08 16:02:47.603  3925  3925 D BluetoothMap: Bluetooth is Not enabled
,09-08 16:02:47.606  4176  4176 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 16:02:47.608  4176  4176 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,09-08 16:02:47.608  4176  4176 D BluetoothMapAppObserver: createReceiver()
,09-08 16:02:47.610  4176  4176 D BluetoothMapAppObserver: initObservers()
09-08 16:02:47.610  4176  4176 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 16:02:47.620  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:02:47.620  4176  4176 V BluetoothAdapterState: isTurningOff()=false
09-08 16:02:47.621  4176  4176 V BluetoothAdapterState: isTurningOn()=true
09-08 16:02:47.621  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:02:47.621  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:02:47.623  4176  4176 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:02:47.623  4176  4176 V BluetoothAdapterState: isTurningOn()=true
09-08 16:02:47.623  4176  4205 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
09-08 16:02:47.623  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:02:47.623  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:47.623  4176  4176 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:02:47.623  4176  4176 V BluetoothAdapterState: isTurningOn()=true
,09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isTurningOff()=false
09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isTurningOn()=true
09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isTurningOff()=false
09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isTurningOn()=true
09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:02:47.624  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:47.625  4176  4176 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:02:47.625  4176  4176 V BluetoothAdapterState: isTurningOn()=true
09-08 16:02:47.625  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:47.625  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:02:47.625  4176  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
09-08 16:02:47.625  4176  4188 D BluetoothAdapterProperties: ScanMode =  20
09-08 16:02:47.625  4176  4188 D BluetoothAdapterProperties: State =  11
09-08 16:02:47.626  4176  4188 D BluetoothAdapterProperties: Setting state to 12
09-08 16:02:47.626  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 16:02:47.627  1363  1375 D BluetoothMap: onBluetoothStateChange: up=true
09-08 16:02:47.627  4176  4192 D BluetoothAdapterProperties: Scan Mode:21
09-08 16:02:47.627  4176  4192 D BluetoothAdapterProperties: Discoverable Timeout:120
09-08 16:02:47.627  4176  4188 I BluetoothAdapterState: Entering OnState
,09-08 16:02:47.630  1363  1374 D BluetoothPan: onBluetoothStateChange on: true
09-08 16:02:47.631  1363  1363 D BluetoothMap: Proxy object connected
09-08 16:02:47.631  1363  1363 D MapProfile: Bluetooth service connected
,09-08 16:02:47.631  1363  1363 D BluetoothMap: getConnectedDevices()
,09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:47.632  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:47.633  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:02:47.633  1363  2065 D BluetoothHeadset: onBluetoothStateChange: up=true
,09-08 16:02:47.634  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 16:02:47.634  1363  1363 D PanProfile: Bluetooth service connected
09-08 16:02:47.634  3925  3938 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 16:02:47.635  4176  4176 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 16:02:47.636   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:02:47.636  4176  4176 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 16:02:47.636  3925  3937 D BluetoothPan: onBluetoothStateChange on: true
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:47.636  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:47.636  1363  1375 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:02:47.637  4176  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:02:47.638  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:02:47.638  1363  2065 D BluetoothPbap: onBluetoothStateChange: up=true
,09-08 16:02:47.638  1363  1363 D BluetoothInputDevice: Proxy object connected
09-08 16:02:47.638  1363  1363 D HidProfile: Bluetooth service connected
09-08 16:02:47.639   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:02:47.640  3925  3938 D BluetoothMap: onBluetoothStateChange: up=true
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:47.640  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:47.640  3925  3937 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:02:47.640  4176  4176 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:02:47.641  1363  1374 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:02:47.642  4176  4176 D ObexServerSockets: Succeed to create listening sockets 
,09-08 16:02:47.642  4176  4176 D ObexServerSockets0: startAccept()
09-08 16:02:47.642  4176  4176 D ObexServerSockets0: prepareForNewConnect()
09-08 16:02:47.642   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:02:47.642  1973  1988 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:02:47.642  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:47.642   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:02:47.643   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 16:02:47.644  4176  4176 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
09-08 16:02:47.644  4176  4176 D BluetoothSdpJni: SDP Create record success - handle: 0
,09-08 16:02:47.645  1363  1363 D BluetoothA2dp: Proxy object connected
09-08 16:02:47.646  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:47.646   876   876 D BluetoothA2dp: Proxy object connected
09-08 16:02:47.646  4176  4176 D BluetoothMapService: onReceive
09-08 16:02:47.646  4176  4176 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 16:02:47.646  4176  4176 D BluetoothMapService: STATE_ON
09-08 16:02:47.646  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:47.647  3925  3925 D LocalBluetoothProfileManager: Adding local A2DP profile
09-08 16:02:47.647  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:47.649  4176  4214 D ObexServerSockets0: Accepting socket connection...
09-08 16:02:47.649  4176  4213 D ObexServerSockets0: Accepting socket connection...
,09-08 16:02:47.653  3925  3925 D LocalBluetoothProfileManager: Adding local HEADSET profile
,09-08 16:02:47.659  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 16:02:47.660  3925  3925 D BluetoothA2dp: Proxy object connected
,09-08 16:02:47.669  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:02:47.670  4176  4176 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 16:02:47.670  4176  4176 D ObexServerSockets0: prepareForNewConnect()
,09-08 16:02:47.671  4176  4216 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:02:47.672  1363  1363 D BluetoothPbap: Proxy object connected
09-08 16:02:47.672  1363  1363 D PbapServerProfile: Bluetooth service connected
,09-08 16:02:47.675  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:02:47.675  3925  3925 D BluetoothPbap: Proxy object connected
09-08 16:02:47.676  3925  3925 D PbapServerProfile: Bluetooth service connected
,09-08 16:02:47.691  4176  4222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:02:47.692  4176  4222 I BtOppRfcommListener: Accept thread started.
,09-08 16:02:47.736   876   876 D BluetoothHeadset: Proxy object connected
,09-08 16:02:47.736  1363  2065 D BluetoothHeadset: Proxy object connected
09-08 16:02:47.736  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-08 16:02:47.736   876   876 D BluetoothHeadset: Proxy object connected
09-08 16:02:47.736   876   876 D BluetoothHeadset: Proxy object connected
09-08 16:02:47.736   876   893 D BluetoothHeadset: Proxy object connected
09-08 16:02:47.736  1973  2122 D BluetoothHeadset: Proxy object connected
,09-08 16:02:47.742   876   893 D BluetoothHeadset: Proxy object connected
,09-08 16:02:47.743  1973  1991 D BluetoothHeadset: Proxy object connected
09-08 16:02:47.743   876   893 D BluetoothHeadset: Proxy object connected
,09-08 16:02:47.757  3925  3938 D BluetoothHeadset: Proxy object connected
,09-08 16:02:47.758  3925  3925 D HeadsetProfile: Bluetooth service connected
,09-08 16:02:49.685  1527  1527 I ConfigService: onDestroy
,09-08 16:02:51.089  4176  4188 D BluetoothAdapterState: Current state: ON, message: 23
,09-08 16:02:51.089  4176  4188 D BluetoothAdapterProperties: Setting state to 13
09-08 16:02:51.089  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
09-08 16:02:51.091  4176  4188 D BluetoothAdapterProperties: onBluetoothDisable()
,09-08 16:02:51.093  4176  4188 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:02:51.106  4176  4192 D BluetoothAdapterProperties: Scan Mode:20
,09-08 16:02:51.107  4176  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,09-08 16:02:51.110  4176  4176 D BluetoothMapService: onReceive
,09-08 16:02:51.113  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:51.114  4176  4176 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:51.114  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:51.115  4176  4176 D BluetoothMapService: STATE_TURNING_OFF
,09-08 16:02:51.116  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:51.117  4176  4176 D BluetoothMapService: MAP Service closeService in
09-08 16:02:51.117  4176  4176 D BluetoothMapMasInstance0: MAP Service shutdown
09-08 16:02:51.117  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:51.118  4176  4176 D ObexServerSockets0: shutdown(block = true)
09-08 16:02:51.122  4176  4176 D ObexServerSockets0: shutdown called from another thread - interrupt().
,09-08 16:02:51.123  4176  4176 D ObexServerSockets0: shutdown called from another thread - interrupt().
09-08 16:02:51.124  4176  4201 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
09-08 16:02:51.124  4176  4214 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
09-08 16:02:51.125  4176  4213 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
09-08 16:02:51.126  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:51.126  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:02:51.126  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:51.127  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:51.127  4176  4176 I BtOppRfcommListener: stopping Accept Thread
,09-08 16:02:51.127  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 16:02:51.129  4176  4222 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
09-08 16:02:51.130  4176  4222 I BtOppRfcommListener: BluetoothSocket listen thread finished
09-08 16:02:51.133  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:02:51.133  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:02:51.134  3865  3865 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,09-08 16:02:51.134  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:02:51.139  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:51.140  4176  4176 D HeadsetService: Received stop request...Stopping profile...
09-08 16:02:51.141   876   876 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:51.142  1363  1374 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:51.142  1363  1363 D HeadsetProfile: Bluetooth service disconnected
09-08 16:02:51.143  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:51.143  3925  3938 D BluetoothHeadset: Proxy object disconnected
,09-08 16:02:51.143   876   876 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:51.143  4176  4176 D A2dpService: Received stop request...Stopping profile...
09-08 16:02:51.143   876   876 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:51.143  4176  4207 D A2dpStateMachine: Exit Disconnected: -1
09-08 16:02:51.143  1973  1988 D BluetoothHeadset: Proxy object disconnected
09-08 16:02:51.144  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:51.146  1363  1363 D BluetoothA2dp: Proxy object disconnected
09-08 16:02:51.146   876   876 D BluetoothA2dp: Proxy object disconnected
09-08 16:02:51.147  4176  4176 D HidService: Received stop request...Stopping profile...
09-08 16:02:51.147  4176  4176 D HidService: Stopping Bluetooth HidService
,09-08 16:02:51.149  1363  1363 D BluetoothInputDevice: Proxy object disconnected
09-08 16:02:51.149  1363  1363 D HidProfile: Bluetooth service disconnected
,09-08 16:02:51.151  4176  4176 D HealthService: Received stop request...Stopping profile...
,09-08 16:02:51.151  3925  3925 D DockEventReceiver: finishStartingService: stopping service
09-08 16:02:51.152  4176  4176 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:51.152  4176  4176 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:51.152  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:51.152  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:51.152  3925  3925 D HeadsetProfile: Bluetooth service disconnected
,09-08 16:02:51.153  3925  3925 D BluetoothA2dp: Proxy object disconnected
,09-08 16:02:51.153  4176  4176 D PanService: Received stop request...Stopping profile...
09-08 16:02:51.154  1363  1363 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 16:02:51.154  1363  1363 D PanProfile: Bluetooth service disconnected
,09-08 16:02:51.154  3925  3925 D BluetoothInputDevice: Proxy object disconnected
09-08 16:02:51.154  3925  3925 D HidProfile: Bluetooth service disconnected
09-08 16:02:51.155  3925  3925 D BluetoothPan: BluetoothPAN Proxy object disconnected
09-08 16:02:51.155  3925  3925 D PanProfile: Bluetooth service disconnected
09-08 16:02:51.155  4176  4176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
09-08 16:02:51.155  4176  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
09-08 16:02:51.156  4176  4198 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:51.156  4176  4176 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
09-08 16:02:51.156  4176  4198 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:51.156  4176  4198 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:51.156  4176  4192 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,09-08 16:02:51.157  4176  4176 D BluetoothMapService: Received stop request...Stopping profile...
09-08 16:02:51.157  4176  4176 D BluetoothMapService: stop()
,09-08 16:02:51.158  4176  4176 D BluetoothMapAppObserver: deinitObservers()
,09-08 16:02:51.158  4176  4176 D BluetoothMapAppObserver: removeReceiver()
09-08 16:02:51.159  1363  1363 D BluetoothMap: Proxy object disconnected
09-08 16:02:51.159  1363  1363 D MapProfile: Bluetooth service disconnected
09-08 16:02:51.160  4176  4176 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:51.160  4176  4176 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:51.160  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:51.160  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:51.161  4176  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,09-08 16:02:51.161  4176  4198 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:51.161  4176  4198 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:51.161  3925  3925 D BluetoothMap: Proxy object disconnected
09-08 16:02:51.161  4176  4198 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 16:02:51.161  3925  3925 D MapProfile: Bluetooth service disconnected
09-08 16:02:51.161  4176  4198 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 16:02:51.162  4176  4198 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
09-08 16:02:51.162  4176  4198 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
09-08 16:02:51.162  4176  4176 V BluetoothAdapterState: isTurningOff()=true
,09-08 16:02:51.162  4176  4176 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:51.163  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:51.163  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:51.164  4176  4176 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
09-08 16:02:51.164  4176  4192 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
09-08 16:02:51.165  4176  4176 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
09-08 16:02:51.165  4176  4176 V BluetoothAdapterState: isTurningOff()=true
,09-08 16:02:51.165  4176  4176 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:51.165  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:51.165  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:51.165  4176  4176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
09-08 16:02:51.166  4176  4192 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
09-08 16:02:51.166  4176  4176 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
09-08 16:02:51.167  4176  4176 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:51.167  4176  4176 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:51.167  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:02:51.167  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:02:51.167  4176  4176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
09-08 16:02:51.167  4176  4176 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,09-08 16:02:51.168  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
09-08 16:02:51.168  4176  4176 D BluetoothMapService: MAP Service closeService in
09-08 16:02:51.168  4176  4176 V BluetoothAdapterState: isTurningOff()=true
09-08 16:02:51.168  4176  4176 V BluetoothAdapterState: isTurningOn()=false
09-08 16:02:51.168  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:02:51.169  4176  4176 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:02:51.169  4176  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
09-08 16:02:51.169  4176  4176 D BluetoothMapService: cleanup()
09-08 16:02:51.169  4176  4188 D BluetoothAdapterProperties: Setting state to 15
09-08 16:02:51.169  4176  4176 D BluetoothMapService: MAP Service closeService in
09-08 16:02:51.169  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
09-08 16:02:51.169  4176  4188 I BluetoothAdapterState: Entering BleOnState
,09-08 16:02:51.172  3925  3937 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 16:02:51.173  1363  1363 D BluetoothPbap: Proxy object disconnected
09-08 16:02:51.173  1363  1363 D PbapServerProfile: Bluetooth service disconnected
,09-08 16:02:51.174  1363  2065 D BluetoothMap: onBluetoothStateChange: up=false
09-08 16:02:51.174  3925  3925 D BluetoothPbap: Proxy object disconnected
09-08 16:02:51.175  3925  3925 D PbapServerProfile: Bluetooth service disconnected
,09-08 16:02:51.177  1363  1374 D BluetoothPan: onBluetoothStateChange on: false
09-08 16:02:51.178  1363  1375 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:02:51.178  3925  3938 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 16:02:51.179   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:02:51.180  3925  3937 D BluetoothPan: onBluetoothStateChange on: false
,09-08 16:02:51.181  1363  2065 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 16:02:51.181  1363  1374 D BluetoothPbap: onBluetoothStateChange: up=false
09-08 16:02:51.182   876   893 D BluetoothA2dp: onBluetoothStateChange: up=false
,09-08 16:02:51.182  3925  4229 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:02:51.182  3925  3938 D BluetoothMap: onBluetoothStateChange: up=false
,09-08 16:02:51.183  3925  3937 D BluetoothInputDevice: onBluetoothStateChange: up=false
09-08 16:02:51.184  1363  1375 D BluetoothA2dp: onBluetoothStateChange: up=false
09-08 16:02:51.184   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
,09-08 16:02:51.184  1973  2122 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:02:51.185   876   893 D BluetoothHeadset: onBluetoothStateChange: up=false
09-08 16:02:51.186  4176  4188 D BluetoothAdapterState: Current state: BLE ON, message: 20
09-08 16:02:51.186  4176  4188 D BluetoothAdapterProperties: Setting state to 16
09-08 16:02:51.186  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,09-08 16:02:51.187  4176  4188 D BluetoothAdapterProperties: onBleDisable
09-08 16:02:51.187  4176  4188 I BluetoothAdapterState: Entering PendingCommandState
09-08 16:02:51.187  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:51.188  4176  4189 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
09-08 16:02:51.188  4176  4192 D BluetoothAdapterProperties: Scan Mode:20
09-08 16:02:51.189  4176  4198 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
09-08 16:02:51.189  4176  4198 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
09-08 16:02:51.189  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
09-08 16:02:51.189  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:51.190  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:02:51.191  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:51.193  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:51.196  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:02:51.196  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:02:51.204  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:02:51.392  4176  4192 I bt_hci  : shut_down
,09-08 16:02:51.405  4176  4196 I bt_vendor: low_power_mode_cb
,09-08 16:02:51.410  4176  4196 D bt_hwcfg: hw_epilog_process
,09-08 16:02:51.428  4176  4196 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
09-08 16:02:51.428  4176  4196 I bt_vendor: epilog_cb
09-08 16:02:51.428  4176  4196 I bt_hci  : epilog_finished_callback
,09-08 16:02:51.436  4176  4192 I bt_hci_h4: hal_close
,09-08 16:02:51.437  4176  4192 I bt_userial_vendor: device fd = 51 close
,09-08 16:02:51.566  4176  4189 D bt_stack_manager: event_shut_down_stack finished.
,09-08 16:02:51.568  4176  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,09-08 16:02:51.574  4176  4176 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 16:02:51.574  4176  4188 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,09-08 16:02:51.575  4176  4176 D BtGatt.GattService: Received stop request...Stopping profile...
,09-08 16:02:51.576  4176  4176 D BtGatt.GattService: stop()
,09-08 16:02:51.576  4176  4176 D BtGatt.AdvertiseManager: advertise clients cleared
,09-08 16:02:51.580  4176  4176 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:02:51.582  4176  4176 V BluetoothAdapterState: isTurningOn()=false
,09-08 16:02:51.582  4176  4176 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:02:51.582  4176  4176 V BluetoothAdapterState: isBleTurningOff()=true
09-08 16:02:51.583  4176  4188 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,09-08 16:02:51.583  4176  4188 D BluetoothAdapterProperties: Setting state to 10
09-08 16:02:51.584  4176  4188 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
09-08 16:02:51.585  4176  4188 I BluetoothAdapterState: Entering OffState
09-08 16:02:51.587   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,09-08 16:02:51.610  4176  4176 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,09-08 16:02:51.611  4176  4176 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,09-08 16:02:51.611  4176  4189 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,09-08 16:02:51.616  4176  4176 I BluetoothServiceJni: cleanupNative: return from cleanup
,09-08 16:02:51.627  4176  4189 D bt_stack_manager: event_clean_up_stack finished.
,09-08 16:02:51.629  4176  4176 I art     : System.exit called, status: 0
09-08 16:02:51.629  4176  4176 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,09-08 16:02:51.677   876  1543 I ActivityManager: Process com.android.bluetooth (pid 4176) has died
,09-08 16:02:56.086  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:02:56.086  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:56.091  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:56.091  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b3b232 removed from the list
09-08 16:02:56.092  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:02:56.092  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:56.092  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:56.095  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:02:56.096  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7664100 added. We now have 4 listener(s)
09-08 16:02:56.096  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:02:56.098  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:02:56.098  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7664100 removed from the list
09-08 16:02:56.099  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:02:56.099  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:02:56.099  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:02:56.101  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:02:56.102  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@457dd39 added. We now have 4 listener(s)
09-08 16:02:56.102  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:03:01.114  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:01.163   876   893 I ActivityManager: Start proc 4238:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,09-08 16:03:01.323  4238  4238 D AdapterServiceConfig: Adding HeadsetService
,09-08 16:03:01.324  4238  4238 D AdapterServiceConfig: Adding A2dpService
09-08 16:03:01.324  4238  4238 D AdapterServiceConfig: Adding HidService
09-08 16:03:01.324  4238  4238 D AdapterServiceConfig: Adding HealthService
09-08 16:03:01.324  4238  4238 D AdapterServiceConfig: Adding PanService
09-08 16:03:01.325  4238  4238 D AdapterServiceConfig: Adding GattService
09-08 16:03:01.325  4238  4238 D AdapterServiceConfig: Adding BluetoothMapService
,09-08 16:03:01.339  4238  4238 D BluetoothAdapterState: make() - Creating AdapterState
,09-08 16:03:01.339   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@83a33ca:true
,09-08 16:03:01.344  4238  4238 I bt_bluedroid: init
,09-08 16:03:01.345  4238  4250 I BluetoothAdapterState: Entering OffState
,09-08 16:03:01.350  4238  4251 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,09-08 16:03:01.350  4238  4251 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
09-08 16:03:01.350  4238  4251 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,09-08 16:03:01.351  4238  4251 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
09-08 16:03:01.353  4238  4238 I bt_bluedroid: get_profile_interface socket
,09-08 16:03:01.356  4238  4254 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 16:03:01.357  4238  4254 D BluetoothAdapterProperties: Name is: Nexus 6
09-08 16:03:01.358  4238  4238 I bt_bluedroid: get_profile_interface sdp
,09-08 16:03:01.365  4238  4249 I bt_bluedroid: config_hci_snoop_log
,09-08 16:03:01.370   876   893 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,09-08 16:03:01.385  4238  4250 D BluetoothAdapterState: Current state: OFF, message: 0
09-08 16:03:01.385  4238  4250 D BluetoothAdapterProperties: Setting state to 14
09-08 16:03:01.386  4238  4250 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
09-08 16:03:01.391  4238  4250 D BluetoothBondStateMachine: make
,09-08 16:03:01.397  4238  4255 I BluetoothBondStateMachine: StableState(): Entering Off State
,09-08 16:03:01.406  4238  4250 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:03:01.410  4238  4238 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,09-08 16:03:01.420  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:03:01.422  4238  4238 D BtGatt.DebugUtils: handleDebugAction() action=null
,09-08 16:03:01.424  4238  4238 D BtGatt.GattService: Received start request. Starting profile...
09-08 16:03:01.424  4238  4238 D BtGatt.GattService: start()
,09-08 16:03:01.426  4238  4238 I bt_bluedroid: get_profile_interface gatt
,09-08 16:03:01.428  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:03:01.428  4238  4238 D BtGatt.AdvertiseManager: advertise manager created
,09-08 16:03:01.440  4238  4238 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:03:01.440  4238  4238 V BluetoothAdapterState: isTurningOn()=false
09-08 16:03:01.440  4238  4238 V BluetoothAdapterState: isBleTurningOn()=true
09-08 16:03:01.440  4238  4238 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:03:01.441  4238  4250 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
09-08 16:03:01.442  4238  4250 I bt_bluedroid: enable
09-08 16:03:01.442  4238  4251 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,09-08 16:03:01.443  4238  4251 I bt_hci  : start_up
,09-08 16:03:01.466  4238  4251 I bt_vendor: alloc value 0xb3a08189
,09-08 16:03:01.466  4238  4251 I bt_vendor: init
09-08 16:03:01.467  4238  4251 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
09-08 16:03:01.467  4238  4251 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,09-08 16:03:01.576  4238  4251 D bt_hci  : start_up starting async portion
,09-08 16:03:01.577  4238  4258 I bt_hci  : event_finish_startup
09-08 16:03:01.577  4238  4258 I bt_hci_h4: hal_open
09-08 16:03:01.578  4238  4258 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,09-08 16:03:01.587  4238  4258 I bt_userial_vendor: device fd = 51 open
,09-08 16:03:01.620  4238  4258 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:03:01.651  4238  4258 D bt_hwcfg: Chipset BCM4354A2
,09-08 16:03:01.652  4238  4258 D bt_hwcfg: Target name = [BCM4354A2]
09-08 16:03:01.652  4238  4258 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,09-08 16:03:02.502  4238  4258 I bt_hwcfg: bt vendor lib: set UART baud 115200
,09-08 16:03:02.504  4238  4258 D bt_hwcfg: Settlement delay -- 100 ms
09-08 16:03:02.505  4238  4258 I bt_hwcfg: Setting fw settlement delay to 100 
,09-08 16:03:02.622  4238  4258 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,09-08 16:03:02.624  4238  4258 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,09-08 16:03:02.651  4238  4258 I bt_hwcfg: vendor lib fwcfg completed
,09-08 16:03:02.652  4238  4258 I bt_vendor: firmware callback
09-08 16:03:02.652  4238  4258 I bt_hci  : firmware_config_callback
,09-08 16:03:02.663  4238  4260 I bt_btu  : btu_task pending for preload complete event
,09-08 16:03:02.663  4238  4260 I bt_btu_task: Bluetooth chip preload is complete
09-08 16:03:02.664  4238  4260 I bt_btu  : btu_task received preload complete event
,09-08 16:03:02.673  4238  4260 I         : BTE_InitTraceLevels -- TRC_HCI
,09-08 16:03:02.674  4238  4260 I         : BTE_InitTraceLevels -- TRC_L2CAP
09-08 16:03:02.674  4238  4260 I         : BTE_InitTraceLevels -- TRC_RFCOMM
09-08 16:03:02.674  4238  4260 I         : BTE_InitTraceLevels -- TRC_AVDT
09-08 16:03:02.675  4238  4260 I         : BTE_InitTraceLevels -- TRC_AVRC
,09-08 16:03:02.675  4238  4260 I         : BTE_InitTraceLevels -- TRC_A2D
09-08 16:03:02.675  4238  4260 I         : BTE_InitTraceLevels -- TRC_BNEP
09-08 16:03:02.675  4238  4260 I         : BTE_InitTraceLevels -- TRC_BTM
09-08 16:03:02.676  4238  4260 I         : BTE_InitTraceLevels -- TRC_GAP
09-08 16:03:02.676  4238  4260 I         : BTE_InitTraceLevels -- TRC_PAN
,09-08 16:03:02.676  4238  4260 I         : BTE_InitTraceLevels -- TRC_SDP
09-08 16:03:02.676  4238  4260 I         : BTE_InitTraceLevels -- TRC_GATT
09-08 16:03:02.677  4238  4260 I         : BTE_InitTraceLevels -- TRC_SMP
09-08 16:03:02.677  4238  4260 I         : BTE_InitTraceLevels -- TRC_BTAPP
,09-08 16:03:02.677  4238  4260 I         : BTE_InitTraceLevels -- TRC_BTIF
,09-08 16:03:02.812  4238  4260 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3985d9d
,09-08 16:03:02.812  4238  4260 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3985d9d 
,09-08 16:03:02.837  4238  4254 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
09-08 16:03:02.839  4238  4254 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,09-08 16:03:02.839  4238  4254 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,09-08 16:03:02.845  4238  4254 D BluetoothAdapterProperties: Name is: Nexus 6
,09-08 16:03:02.848  4238  4254 D BluetoothAdapterProperties: Scan Mode:20
,09-08 16:03:02.848  4238  4254 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 16:03:02.849  4238  4254 D bt_hci  : do_postload posting postload work item
,09-08 16:03:02.849  4238  4258 I bt_hci  : event_postload
,09-08 16:03:02.850  4238  4258 I bt_vendor: sco_config_cb
,09-08 16:03:02.850  4238  4258 I bt_hci  : sco_config_callback postload finished.
09-08 16:03:02.852  4238  4254 D bt_bte_conf: Device ID record 1 : primary
,09-08 16:03:02.852  4238  4254 D bt_bte_conf:   vendorId            = 000f
09-08 16:03:02.852  4238  4254 D bt_bte_conf:   vendorIdSource      = 0001
,09-08 16:03:02.853  4238  4254 D bt_bte_conf:   product             = 1200
,09-08 16:03:02.853  4238  4254 D bt_bte_conf:   version             = 1436
,09-08 16:03:02.853  4238  4254 D bt_bte_conf:   clientExecutableURL = 
09-08 16:03:02.853  4238  4254 D bt_bte_conf:   serviceDescription  = 
,09-08 16:03:02.853  4238  4254 D bt_bte_conf:   documentationURL    = 
09-08 16:03:02.854  4238  4254 D bt_bte_conf: bte_load_did_conf no section named DID2.
,09-08 16:03:02.854  4238  4251 D bt_stack_manager: event_start_up_stack finished
,09-08 16:03:02.855  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:02.857  4238  4250 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
09-08 16:03:02.858  4238  4258 I bt_vendor: low_power_mode_cb
09-08 16:03:02.858  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:03:02.858  4238  4250 D BluetoothAdapterProperties: Setting state to 15
09-08 16:03:02.859  4238  4250 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,09-08 16:03:02.860  4238  4250 I BluetoothAdapterState: Entering BleOnState
09-08 16:03:02.865  4238  4250 D BluetoothAdapterState: Current state: BLE ON, message: 1
09-08 16:03:02.866  4238  4250 D BluetoothAdapterProperties: Setting state to 11
09-08 16:03:02.866  4238  4250 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
09-08 16:03:02.875  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:03:02.879  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:02.879  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
09-08 16:03:02.880  4238  4238 D HeadsetService: Received start request. Starting profile...
09-08 16:03:02.882  4238  4238 I BluetoothHeadsetServiceJni: classInitNative: succeeds
09-08 16:03:02.883  4238  4238 D HeadsetStateMachine: make
,09-08 16:03:02.894  4238  4238 D HeadsetStateMachine: max_hf_connections = 1
,09-08 16:03:02.894  4238  4238 I bt_bluedroid: get_profile_interface handsfree
09-08 16:03:02.894  4238  4254 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
09-08 16:03:02.894  4238  4254 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
09-08 16:03:02.897  4238  4250 I BluetoothAdapterState: Entering PendingCommandState
,09-08 16:03:02.900  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:03:02.900  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
09-08 16:03:02.901  4238  4238 D A2dpService: Received start request. Starting profile...
,09-08 16:03:02.902  4238  4238 I BluetoothAvrcpServiceJni: classInitNative: succeeds
09-08 16:03:02.902  4238  4238 I bt_bluedroid: get_profile_interface avrcp
,09-08 16:03:02.908  4238  4238 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,09-08 16:03:02.908  4238  4238 I BluetoothA2dpServiceJni: classInitNative: succeeds
09-08 16:03:02.908  4238  4238 D A2dpStateMachine: make
,09-08 16:03:02.910  4238  4238 I bt_bluedroid: get_profile_interface a2dp
,09-08 16:03:02.910  4238  4254 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,09-08 16:03:02.912  4238  4269 D A2dpStateMachine: Enter Disconnected: -2
09-08 16:03:02.912  4238  4238 I BluetoothHidServiceJni: classInitNative: succeeds
,09-08 16:03:02.913  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
09-08 16:03:02.914  4238  4238 D HidService: Received start request. Starting profile...
09-08 16:03:02.914  4238  4238 I bt_bluedroid: get_profile_interface hidhost
09-08 16:03:02.914  4238  4238 D HidService: setHidService(): set to: null
09-08 16:03:02.914  4238  4254 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39673e5
,09-08 16:03:02.914  4238  4254 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
09-08 16:03:02.916  4238  4238 I BluetoothHealthServiceJni: classInitNative: succeeds
,09-08 16:03:02.917  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
09-08 16:03:02.917  4238  4238 D HealthService: Received start request. Starting profile...
,09-08 16:03:02.919  4238  4238 I bt_bluedroid: get_profile_interface health
,09-08 16:03:02.919  4238  4238 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,09-08 16:03:02.920  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
09-08 16:03:02.921  4238  4238 D PanService: Received start request. Starting profile...
,09-08 16:03:02.921  4238  4238 D BluetoothPanServiceJni: initializeNative(L110): pan
09-08 16:03:02.921  4238  4238 I bt_bluedroid: get_profile_interface pan
09-08 16:03:02.922  4238  4254 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,09-08 16:03:02.924  4238  4238 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:03:02.924  4238  4238 D BluetoothMapService: Received start request. Starting profile...
09-08 16:03:02.924  4238  4238 D BluetoothMapService: start()
,09-08 16:03:02.926  4238  4238 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,09-08 16:03:02.927  4238  4238 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
09-08 16:03:02.927  4238  4238 D BluetoothMapAppObserver: createReceiver()
,09-08 16:03:02.928  4238  4238 D BluetoothMapAppObserver: initObservers()
09-08 16:03:02.928  4238  4238 D BluetoothMapAppObserver: getEnabledAccountItems()
,09-08 16:03:02.934  4238  4238 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:03:02.934  4238  4238 V BluetoothAdapterState: isTurningOn()=true
09-08 16:03:02.934  4238  4238 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:03:02.934  4238  4238 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:03:02.936  4238  4267 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,09-08 16:03:02.937  4238  4238 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:03:02.937  4238  4238 V BluetoothAdapterState: isTurningOn()=true
09-08 16:03:02.937  4238  4238 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:03:02.937  4238  4238 V BluetoothAdapterState: isBleTurningOff()=false
,09-08 16:03:02.937  4238  4238 V BluetoothAdapterState: isTurningOff()=false
09-08 16:03:02.938  4238  4238 V BluetoothAdapterState: isTurningOn()=true
09-08 16:03:02.938  4238  4238 V BluetoothAdapterState: isBleTurningOn()=false
09-08 16:03:02.938  4238  4238 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:03:02.938  4238  4238 V BluetoothAdapterState: isTurningOff()=false,
09-08 16:03:02.939  4238  4238 V BluetoothAdapterState: isTurningOn()=true
09-08 16:03:02.939  4238  4238 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:03:02.939  4238  4238 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:03:02.939  4238  4238 V BluetoothAdapterState: isTurningOff()=false
09-08 16:03:02.939  4238  4238 V BluetoothAdapterState: isTurningOn()=true
09-08 16:03:02.940  4238  4238 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:03:02.940  4238  4238 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:03:02.940  4238  4238 V BluetoothAdapterState: isTurningOff()=false
,09-08 16:03:02.940  4238  4238 V BluetoothAdapterState: isTurningOn()=true
,09-08 16:03:02.940  4238  4238 V BluetoothAdapterState: isBleTurningOn()=false
,09-08 16:03:02.940  4238  4238 V BluetoothAdapterState: isBleTurningOff()=false
09-08 16:03:02.940  4238  4250 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,09-08 16:03:02.940  4238  4250 D BluetoothAdapterProperties: ScanMode =  20
,09-08 16:03:02.940  4238  4250 D BluetoothAdapterProperties: State =  11
09-08 16:03:02.942  4238  4254 D BluetoothAdapterProperties: Scan Mode:21
09-08 16:03:02.942  4238  4254 D BluetoothAdapterProperties: Discoverable Timeout:120
,09-08 16:03:02.942  4238  4250 D BluetoothAdapterProperties: Setting state to 12
,09-08 16:03:02.942  4238  4250 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
09-08 16:03:02.943  4238  4250 I BluetoothAdapterState: Entering OnState
09-08 16:03:02.943  3925  3937 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:03:02.945  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:03:02.947  1363  1374 D BluetoothMap: onBluetoothStateChange: up=true
09-08 16:03:02.947  3925  3925 D BluetoothA2dp: Proxy object connected
09-08 16:03:02.947  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:03:02.949  1363  1363 D BluetoothMap: Proxy object connected
,09-08 16:03:02.949  1363  1363 D MapProfile: Bluetooth service connected
09-08 16:03:02.949  1363  1363 D BluetoothMap: getConnectedDevices()
,09-08 16:03:02.949  1363  2065 D BluetoothPan: onBluetoothStateChange on: true
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:03:02.951  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
09-08 16:03:02.952  1363  1363 D BluetoothPan: BluetoothPAN Proxy object connected
,09-08 16:03:02.952  1363  1363 D PanProfile: Bluetooth service connected
09-08 16:03:02.952  1363  1374 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:03:02.953  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
09-08 16:03:02.953  3925  3938 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 16:03:02.954  4238  4238 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
09-08 16:03:02.955  4238  4238 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,09-08 16:03:02.955   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:03:02.955  3925  3937 D BluetoothPan: onBluetoothStateChange on: true
09-08 16:03:02.956  4238  4238 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:03:02.957  1363  2065 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:03:02.958  3925  3925 D BluetoothPan: BluetoothPAN Proxy object connected
09-08 16:03:02.958  3925  3925 D PanProfile: Bluetooth service connected
09-08 16:03:02.958  4238  4238 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:03:02.959  4238  4238 D ObexServerSockets: Succeed to create listening sockets 
09-08 16:03:02.959  4238  4238 D ObexServerSockets0: startAccept()
09-08 16:03:02.959  4238  4238 D ObexServerSockets0: prepareForNewConnect()
,09-08 16:03:02.959  1363  1375 D BluetoothPbap: onBluetoothStateChange: up=true
09-08 16:03:02.961   876   893 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:03:02.961   876   876 D BluetoothA2dp: Proxy object connected
09-08 16:03:02.962  3925  3938 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:03:02.962  4238  4275 D ObexServerSockets0: Accepting socket connection...
09-08 16:03:02.962  4238  4276 D ObexServerSockets0: Accepting socket connection...
09-08 16:03:02.962  3925  4229 D BluetoothMap: onBluetoothStateChange: up=true
,09-08 16:03:02.963  4238  4238 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,09-08 16:03:02.963  4238  4238 D BluetoothSdpJni: SDP Create record success - handle: 0
09-08 16:03:02.964  1363  1363 D BluetoothInputDevice: Proxy object connected
,09-08 16:03:02.964  1363  1363 D HidProfile: Bluetooth service connected
,09-08 16:03:02.965  3925  3938 D BluetoothInputDevice: onBluetoothStateChange: up=true
09-08 16:03:02.967  1363  2065 D BluetoothA2dp: onBluetoothStateChange: up=true
09-08 16:03:02.967  3925  3925 D BluetoothMap: Proxy object connected
09-08 16:03:02.968  3925  3925 D MapProfile: Bluetooth service connected
09-08 16:03:02.968  3925  3925 D BluetoothMap: getConnectedDevices()
09-08 16:03:02.969  1363  1363 D BluetoothA2dp: Proxy object connected
09-08 16:03:02.969   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:03:02.970  1973  1988 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:03:02.970   876   893 D BluetoothHeadset: onBluetoothStateChange: up=true
09-08 16:03:02.970  3925  3925 D BluetoothInputDevice: Proxy object connected
09-08 16:03:02.970  3925  3925 D HidProfile: Bluetooth service connected
,09-08 16:03:02.971   876   876 I Telecom : BluetoothPhoneService: queryPhoneState
09-08 16:03:02.972  4238  4238 D BluetoothMapService: onReceive
09-08 16:03:02.972  4238  4238 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,09-08 16:03:02.972  4238  4238 D BluetoothMapService: STATE_ON
09-08 16:03:02.974  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:03:02.975  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:03:02.978  3925  3925 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,09-08 16:03:02.983  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,09-08 16:03:02.983  3925  3925 D DockEventReceiver: finishStartingService: stopping service
,09-08 16:03:02.990  3925  3925 D BluetoothPbap: Proxy object connected
09-08 16:03:02.990  3925  3925 D PbapServerProfile: Bluetooth service connected
,09-08 16:03:02.995  1363  1363 D BluetoothPbap: Proxy object connected
,09-08 16:03:02.995  1363  1363 D PbapServerProfile: Bluetooth service connected
,09-08 16:03:02.998  4238  4281 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:03:03.009  4238  4238 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,09-08 16:03:03.009  4238  4238 D ObexServerSockets0: prepareForNewConnect()
,09-08 16:03:03.013  4238  4285 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-08 16:03:03.013  4238  4285 I BtOppRfcommListener: Accept thread started.
,09-08 16:03:03.054   876   876 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.055  1363  1375 D BluetoothHeadset: Proxy object connected
09-08 16:03:03.055  1363  1363 D HeadsetProfile: Bluetooth service connected
,09-08 16:03:03.055  3925  3937 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.055   876   893 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.056   876   876 D BluetoothHeadset: Proxy object connected
09-08 16:03:03.056   876   876 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.056  3925  3925 D HeadsetProfile: Bluetooth service connected
,09-08 16:03:03.056  1973  2122 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.063  3925  3938 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.064  3925  3925 D HeadsetProfile: Bluetooth service connected
,09-08 16:03:03.069   876   893 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.071  1973  1991 D BluetoothHeadset: Proxy object connected
,09-08 16:03:03.071   876   893 D BluetoothHeadset: Proxy object connected
,09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:03:06.134  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:03:06.141  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:03:06.143  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:03:06.143  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@457dd39 removed from the list
09-08 16:03:06.143  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:03:06.144  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:03:06.144  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:06.148  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:03:06.148  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e6bf7e added. We now have 4 listener(s)
,09-08 16:03:06.149  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:03:06.153   876   886 D WifiService: setWifiEnabled: false pid=3865, uid=10000
,09-08 16:03:06.153   876   886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:03:11.167  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:11.168   876  3160 D WifiService: setWifiEnabled: true pid=3865, uid=10000
,09-08 16:03:11.168   876  3160 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,09-08 16:03:11.184   876  1316 D WifiConfigStore: Loading config and enabling all networks 
,09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:03:11.199  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:03:11.204  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:03:11.212   876  1316 D WifiConfigStore: loaded 0 passpoint configs
,09-08 16:03:11.213   876  1316 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
09-08 16:03:11.213  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,09-08 16:03:11.214   876  1316 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
09-08 16:03:11.215   876  1316 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
09-08 16:03:11.215   876  1316 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
09-08 16:03:11.216   876  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,09-08 16:03:11.216   876  1316 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
09-08 16:03:11.219  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,09-08 16:03:11.229   373   874 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
09-08 16:03:11.230   876  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:03:11.231   373   874 D CommandListener: Setting iface cfg
,09-08 16:03:11.232   876  1315 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '159 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 159 Failed to set address (No such device)'
,09-08 16:03:11.232   876  1315 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,09-08 16:03:11.286   876  1315 D WifiNative-HAL: p2pGetDeviceAddress
,09-08 16:03:11.287   876  1315 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
09-08 16:03:11.287   876  1316 E native  : do suspend true
,09-08 16:03:11.331   876  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:03:12.600   876  1316 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,09-08 16:03:12.738   876  1316 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.31 rxSuccessRate=14.06 delta 1000 -> 994
09-08 16:03:12.740   876  1316 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,09-08 16:03:12.740   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:03:12.755   876  1316 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,09-08 16:03:12.839   876  1316 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,09-08 16:03:12.846  1470  1470 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,09-08 16:03:13.290  1470  1470 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,09-08 16:03:13.333  1470  1470 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,09-08 16:03:13.335  1470  1470 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,09-08 16:03:13.342   876  1316 D WifiConfigStore: Retrieve network priorities after PNO.
,09-08 16:03:13.358   876  1316 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,09-08 16:03:13.359   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:03:13.358   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,09-08 16:03:13.378   876  1316 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-08 16:03:13.396   373   874 D CommandListener: Setting iface cfg
,09-08 16:03:13.398   876  1316 D WifiStateMachine: Start Dhcp Watchdog 3
,09-08 16:03:13.414   876  4295 D DhcpClient: Receive thread started
,09-08 16:03:13.418   876  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,09-08 16:03:13.522   876  1316 E native  : do suspend false
,09-08 16:03:13.552   876  1935 D DhcpClient: Broadcasting DHCPDISCOVER
,09-08 16:03:13.566   876  4295 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.101, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,09-08 16:03:13.568   876  1935 D DhcpClient: Got pending lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,09-08 16:03:13.571   876  1935 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.101 serverid=192.168.1.1
,09-08 16:03:13.591   876  4295 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.101, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,09-08 16:03:13.592   876  1935 D DhcpClient: Confirmed lease: IP address 192.168.1.101/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,09-08 16:03:13.597   373   874 D CommandListener: Setting iface cfg
,09-08 16:03:13.609   876  1935 D DhcpClient: Scheduling renewal in 86399s
,09-08 16:03:13.609   876  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,09-08 16:03:13.613   876  1316 E native  : do suspend true
,09-08 16:03:13.641   876  1316 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,09-08 16:03:13.645   876  1316 D WifiConfigStore: No blacklist allowed without epno enabled
,09-08 16:03:13.647   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED,
09-08 16:03:13.649   876  1318 D ConnectivityService: Adding iface wlan0 to network 102
,09-08 16:03:13.662   876  1316 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,09-08 16:03:13.740   876  1318 E ConnectivityService: Unexpected mtu value: 0, wlan0
,09-08 16:03:13.741   876  1318 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
09-08 16:03:13.742   876  1318 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,09-08 16:03:13.743   876  1318 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,09-08 16:03:13.746   876  1318 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,09-08 16:03:13.757   876  1318 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 16:03:13.764   876  1318 D ConnectivityService: scheduleUnvalidatedPrompt 102
,09-08 16:03:13.764   876  1318 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
09-08 16:03:13.765   876  1318 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
,09-08 16:03:13.765   876  1318 D ConnectivityService:    accepting network in place of null
09-08 16:03:13.765   876  1316 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,09-08 16:03:13.766   876  1318 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.101/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
09-08 16:03:13.767   876  1316 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,09-08 16:03:13.783   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=411344, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:03:13.818   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:03:13.847   373   874 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,09-08 16:03:13.854   876  1318 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,09-08 16:03:13.855   876  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,09-08 16:03:13.860   876  4293 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,09-08 16:03:13.862   876  1318 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
09-08 16:03:13.865   876   893 D Tethering: MasterInitialState.processMessage what=3
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:13.889  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:13.891  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:13.896  3865  3865 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:13.896  1766  1766 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,09-08 16:03:13.898  3865  3865 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:03:13.901  1766  1766 D SystemUpdateService: onCreate
,09-08 16:03:13.904  1766  1766 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,09-08 16:03:13.925  1766  1766 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,09-08 16:03:13.927  1766  2430 I iu.UploadsManager: num queued entries: 0
,09-08 16:03:13.929  1766  4305 I SystemUpdateService: active receiver: enabled
,09-08 16:03:13.934   876  4293 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 08 Sep 2016 14:03:13 GMT], X-Android-Received-Millis=[1473343393933], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1473343393910]}
,09-08 16:03:13.935   876  1318 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
09-08 16:03:13.935   876  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
09-08 16:03:13.935   876  1318 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,09-08 16:03:13.937   876  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,09-08 16:03:13.941  1766  2430 I iu.UploadsManager: num updated entries: 0
,09-08 16:03:13.943  1766  4305 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,09-08 16:03:13.945  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,09-08 16:03:13.946  1766  1766 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,09-08 16:03:13.948  4006  4006 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
09-08 16:03:13.951  1766  4307 I MDM     : [182] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
09-08 16:03:13.951  1766  4307 W BaseAppContext: Using Auth Proxy for data requests.
,09-08 16:03:13.954  1766  4307 V GoogleAuthProtoRequest: [182] a.<init>: mAccountName set to: thalitester@gmail.com
,09-08 16:03:13.954  4006  4006 D SprintDMHelper: simOperator: 
09-08 16:03:13.954  4006  4006 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,09-08 16:03:13.964  1766  2430 I iu.SyncManager: NEXT; no task
,09-08 16:03:13.970  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:03:13.971  1766  4305 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
09-08 16:03:13.971  1766  4305 I SystemUpdateService: now status is 0 (complete)
,09-08 16:03:13.971  1766  4305 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
09-08 16:03:13.973  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:03:13.997  1766  4305 I SystemUpdateService: file has been verified
09-08 16:03:13.997  1766  4305 I SystemUpdateService: OTA package size = 12249756
,09-08 16:03:14.038  1766  4305 I SystemUpdateService: showing system update notification
,09-08 16:03:14.062  1766  1766 D SystemUpdateService: onDestroy
,09-08 16:03:14.069  1527  2184 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
09-08 16:03:14.069  1527  2184 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
09-08 16:03:14.069  1527  2184 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:03:14.069  1527  2184 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:03:14.089  3976  4311 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,09-08 16:03:14.094  1766  4307 E MDM     : [182] SitrepService.a: Error sending sitrep.
,09-08 16:03:14.854   876  1318 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:16.195  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:16.201  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:03:16.202  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:03:16.202  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1e6bf7e removed from the list
,09-08 16:03:16.203  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
,09-08 16:03:16.203  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:03:16.203  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:16.215  3865  4318 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
,09-08 16:03:16.216  3865  4318 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 16:03:19.222  3865  4319 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,09-08 16:03:19.223  3865  4318 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,09-08 16:03:19.225  3865  4318 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 16:03:19.226  3865  4318 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:03:19.226  3865  4319 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,09-08 16:03:19.227  3865  4319 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:03:19.227  3865  4318 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 16:03:19.230  3865  4321 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 424, name: OutgoingSocketThread/Sender)
09-08 16:03:19.230  3865  4318 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 16:03:19.230  3865  4319 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:03:19.232  3865  4319 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-08 16:03:19.236  3865  4323 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 426, name: OutgoingSocketThread/Receiver)
,09-08 16:03:19.238  3865  4323 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 426, thread name: OutgoingSocketThread/Receiver)
,09-08 16:03:19.239  3865  4323 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 16:03:19.239  3865  4323 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 426, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-08 16:03:19.240  3865  4322 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 425, name: IncomingSocketThread/Sender)
,09-08 16:03:19.242  3865  4324 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 427, name: IncomingSocketThread/Receiver)
09-08 16:03:19.245  3865  4324 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 427, thread name: IncomingSocketThread/Receiver)
,09-08 16:03:19.245  3865  4324 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-08 16:03:19.246  3865  4324 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 427, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 16:03:21.772   876  1318 D ConnectivityService: handlePromptUnvalidated 102
,09-08 16:03:22.222  3865  3911 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,09-08 16:03:22.226  3865  3911 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,09-08 16:03:22.233  3865  3911 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@c4b1548 Bundle[{}]
,09-08 16:03:22.234  3865  3911 I io.jxcore.node.LifeCycleMonitor: start: OK
09-08 16:03:22.234  3865  3911 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-08 16:03:22.234  3865  3911 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,09-08 16:03:22.235  3865  3911 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,09-08 16:03:22.235  3865  3911 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-08 16:03:22.236  3865  3911 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,09-08 16:03:22.240  3865  3911 I System.out: Running OutgoingSocketThread
,09-08 16:03:22.244  3865  4325 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
,09-08 16:03:22.244  3865  4325 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-08 16:03:25.253  3865  4326 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,09-08 16:03:25.254  3865  4326 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-08 16:03:25.254  3865  4326 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:03:25.254  3865  4325 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,09-08 16:03:25.255  3865  4325 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-08 16:03:25.255  3865  4325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:03:25.256  3865  4326 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-08 16:03:25.257  3865  4325 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 16:03:25.260  3865  4328 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 436, name: IncomingSocketThread/Sender)
09-08 16:03:25.261  3865  4326 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
,09-08 16:03:25.264  3865  4329 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 437, name: OutgoingSocketThread/Sender)
,09-08 16:03:25.267  3865  4325 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,09-08 16:03:25.273  3865  4330 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 438, name: IncomingSocketThread/Receiver)
,09-08 16:03:25.274  3865  4330 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 438, thread name: IncomingSocketThread/Receiver)
,09-08 16:03:25.275  3865  4330 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,09-08 16:03:25.275  3865  4330 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 438, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
,09-08 16:03:25.275  3865  4331 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 439, name: OutgoingSocketThread/Receiver)
,09-08 16:03:25.276  3865  4331 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 439, thread name: OutgoingSocketThread/Receiver)
09-08 16:03:25.277  3865  4331 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-08 16:03:25.277  3865  4331 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 439, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,09-08 16:03:28.255  3865  3911 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 448)
,09-08 16:03:28.257  3865  3911 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,09-08 16:03:28.258  3865  3911 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 449)
,09-08 16:03:28.265  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:03:28.265  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c1cdf added. We now have 3 listener(s)
,09-08 16:03:28.266  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:03:28.267  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:03:28.267  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:03:28.267  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:03:28.267  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46e6d2c added. We now have 4 listener(s)
09-08 16:03:28.267  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:03:28.269  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:03:28.278  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:28.291  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:28.297  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:28.298  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:03:28.298  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:03:28.298  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:03:28.298  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:03:28.299  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:28.299  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:28.299  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:03:28.299  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:03:28.299  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c1cdf removed from the list
09-08 16:03:28.299  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:03:28.299  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46e6d2c removed from the list
,09-08 16:03:28.304  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:03:28.304  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:03:28.305  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:03:28.305  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:28.305  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:28.307  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:28.307  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:03:28.308  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:03:28.309  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46e6d2c not in the list
09-08 16:03:28.309  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:03:28.309  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:03:28.312  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:03:28.312  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:28.313  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:28.313  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46e6d2c not in the list
09-08 16:03:28.313  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:03:28.313  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:28.313  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:28.313  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:03:28.314  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@70c1cdf not in the list
09-08 16:03:28.316  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 16:03:28.316  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab558a added. We now have 3 listener(s)
,09-08 16:03:28.322  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:03:28.322  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-08 16:03:28.323  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:03:28.323  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:03:28.324  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbfa7fb added. We now have 4 listener(s)
,09-08 16:03:28.324  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:03:28.325  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:03:28.330  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:28.342  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:28.346  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:03:28.346  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:03:28.346  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:03:28.346  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 16:03:28.346  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,09-08 16:03:28.346  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:03:28.347  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-08 16:03:28.351  3865  3911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 16:03:28.352  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-08 16:03:28.352  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:28.361  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:03:28.361  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:28.362  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 16:03:28.362  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:03:28.371  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,09-08 16:03:28.371  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:03:28.371  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
09-08 16:03:28.373  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:03:28.379  4238  4266 D BtGatt.GattService: registerClient() - UUID=b6918963-f734-4de8-9720-9b36ea125bf5
,09-08 16:03:28.381  4238  4254 D BtGatt.GattService: onClientRegistered() - UUID=b6918963-f734-4de8-9720-9b36ea125bf5, clientIf=5
,09-08 16:03:28.382  3865  3876 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 16:03:28.385  4238  4266 D BtGatt.GattService: start scan with filters
,09-08 16:03:28.396  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 16:03:28.396  4238  4257 D BtGatt.ScanManager: handling starting scan
09-08 16:03:28.396  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 16:03:28.396  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,09-08 16:03:28.397  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,09-08 16:03:28.400  4238  4257 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@dd95f5c
,09-08 16:03:28.408  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:03:28.409  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:03:28.410  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 16:03:28.415  4238  4254 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 16:03:28.415  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:28.417  4238  4257 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:03:28.417  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:03:28.425  3865  3911 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,09-08 16:03:28.425  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 16:03:28.425  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,09-08 16:03:28.426  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:28.426  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:03:28.426  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:03:28.426  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:03:28.426  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:03:28.426  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,09-08 16:03:28.427  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:03:28.429  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 16:03:28.431  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:03:28.433  4238  4254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
09-08 16:03:28.434  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:28.434  4238  4248 D BtGatt.GattService: stopScan() - queue size =1
09-08 16:03:28.435  4238  4257 D BtGatt.ScanManager: Starting BLE batch scan
09-08 16:03:28.435  4238  4257 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 16:03:28.436  4238  4266 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:03:28.438  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:03:28.438  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
09-08 16:03:28.438  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 16:03:28.439  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
09-08 16:03:28.439  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:03:28.442  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:03:28.443  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,09-08 16:03:28.443  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:03:28.443  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:03:28.445  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:03:28.449  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,09-08 16:03:28.449  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:03:28.449  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,09-08 16:03:28.455  4238  4254 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 16:03:28.455  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:03:28.464  4238  4254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 16:03:28.464  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:03:28.477  4238  4254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,09-08 16:03:28.478  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:28.478  4238  4257 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:03:28.492  4238  4254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,09-08 16:03:28.492  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:28.493  4238  4257 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:03:28.504  4238  4254 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
09-08 16:03:28.505  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:03:28.951  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
09-08 16:03:28.951  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:03:28.952  3865  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:03:31.450  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:03:31.451  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:03:31.451  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-08 16:03:31.453  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:31.453  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:31.455  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:03:31.455  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:03:31.457  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab558a removed from the list
,09-08 16:03:31.457  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:03:31.460  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbfa7fb removed from the list
09-08 16:03:31.460  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:03:31.461  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:31.463  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:31.463  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:31.466  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:03:31.467  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:03:31.467  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:31.467  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbfa7fb not in the list
,09-08 16:03:31.468  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:31.468  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:31.472  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:03:31.472  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,09-08 16:03:31.472  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:31.473  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fbfa7fb not in the list
09-08 16:03:31.473  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,09-08 16:03:31.473  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:31.474  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:03:31.474  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ab558a not in the list
09-08 16:03:31.476  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,09-08 16:03:31.477  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36f35c4 added. We now have 3 listener(s)
,09-08 16:03:31.484  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:03:31.484  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:03:31.485  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:03:31.486  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:03:31.486  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@253ccad added. We now have 4 listener(s)
09-08 16:03:31.486  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:03:31.489  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:03:31.496  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:31.504  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:31.507  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:03:31.507  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:03:31.508  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 16:03:31.509  3865  3911 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-08 16:03:31.509  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-08 16:03:31.509  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-08 16:03:31.509  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-08 16:03:31.509  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-08 16:03:31.509  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:03:31.514  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,09-08 16:03:31.514  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:31.514  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-08 16:03:31.515  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-08 16:03:31.515  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-08 16:03:31.515  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-08 16:03:31.515  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-08 16:03:31.515  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 16:03:31.521  3865  4333 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-08 16:03:31.522  3865  3911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
09-08 16:03:31.522  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 16:03:31.531  3865  4333 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,09-08 16:03:31.532  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:31.532  3865  3865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-08 16:03:31.534  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:03:31.538  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
09-08 16:03:31.538  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:03:31.540  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
09-08 16:03:31.541  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,09-08 16:03:31.541  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
09-08 16:03:31.542  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 16:03:31.542  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
09-08 16:03:31.543  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
09-08 16:03:31.543  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:03:31.546  4238  4266 D BtGatt.GattService: registerClient() - UUID=2ac7a5c1-7baa-41a9-b11d-58eea2392981
09-08 16:03:31.546  4238  4254 D BtGatt.GattService: onClientRegistered() - UUID=2ac7a5c1-7baa-41a9-b11d-58eea2392981, clientIf=5
,09-08 16:03:31.547  3865  3876 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,09-08 16:03:31.549  4238  4256 D BtGatt.AdvertiseManager: message : 0
,09-08 16:03:31.551  4238  4256 D BtGatt.AdvertiseManager: starting multi advertising
,09-08 16:03:31.562  4238  4254 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,09-08 16:03:31.570  4238  4254 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,09-08 16:03:31.571  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,09-08 16:03:31.572  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 16:03:31.573  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:03:31.575  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,09-08 16:03:31.575  3865  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
09-08 16:03:31.576  3865  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,09-08 16:03:31.576  3865  3865 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
09-08 16:03:31.576  3865  3865 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
09-08 16:03:31.576  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,09-08 16:03:31.577  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 16:03:31.580  3865  3865 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
09-08 16:03:31.580  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,09-08 16:03:32.082  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
09-08 16:03:32.082  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,09-08 16:03:32.082  3865  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:03:34.579  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:03:34.579  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
09-08 16:03:34.579  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:03:34.580  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,09-08 16:03:34.580  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-08 16:03:34.580  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-08 16:03:34.582  3865  4333 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-08 16:03:34.582  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,09-08 16:03:34.582  3865  4333 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-08 16:03:34.582  3865  3911 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,09-08 16:03:34.583  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:03:34.583  3865  3865 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-08 16:03:34.583  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:03:34.582  3865  4333 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,09-08 16:03:34.583  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,09-08 16:03:34.583  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 16:03:34.584  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-08 16:03:34.586  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:03:34.587  3865  3911 D BluetoothLeScanner: could not find callback wrapper
09-08 16:03:34.587  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:03:34.587  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
09-08 16:03:34.589  4238  4256 D BtGatt.AdvertiseManager: message : 1
09-08 16:03:34.591  4238  4256 D BtGatt.AdvertiseManager: stop advertise for client 5
,09-08 16:03:34.602  4238  4254 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
09-08 16:03:34.602  4238  4254 D BtGatt.GattService: Client app is not null!
,09-08 16:03:34.603  4238  4248 D BtGatt.GattService: unregisterClient() - clientIf=5
09-08 16:03:34.604  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 16:03:34.605  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,09-08 16:03:34.605  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
09-08 16:03:34.605  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
09-08 16:03:34.606  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
,09-08 16:03:34.608  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:03:34.609  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:03:34.609  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-08 16:03:34.610  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:03:34.612  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:03:34.613  3865  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:03:34.613  3865  3865 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-08 16:03:34.613  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:03:34.613  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:03:34.613  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:03:34.614  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:34.614  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:34.614  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:03:34.614  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:03:34.614  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36f35c4 removed from the list
09-08 16:03:34.614  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:34.614  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@253ccad removed from the list
09-08 16:03:34.614  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:03:34.614  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:34.615  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:34.615  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:03:34.617  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:34.618  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:03:34.618  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:34.618  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@253ccad not in the list
09-08 16:03:34.619  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:34.619  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:34.620  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:03:34.621  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:34.621  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:34.621  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@253ccad not in the list
09-08 16:03:34.621  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:34.621  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:34.621  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:03:34.621  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36f35c4 not in the list
09-08 16:03:34.622  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 16:03:34.622  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@500042e added. We now have 3 listener(s)
09-08 16:03:34.624  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:03:34.624  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:03:34.624  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:03:34.624  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,09-08 16:03:34.624  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdbfbcf added. We now have 4 listener(s)
09-08 16:03:34.625  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-08 16:03:34.626  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:03:34.634  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:34.642  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:34.647  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:03:34.648  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
09-08 16:03:34.648  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:03:34.649  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,09-08 16:03:34.649  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-08 16:03:34.649  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:03:34.649  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-08 16:03:34.651  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:03:34.653  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:34.656  3865  3911 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,09-08 16:03:34.656  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-08 16:03:34.662  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-08 16:03:34.662  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,09-08 16:03:34.663  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,09-08 16:03:34.667  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
09-08 16:03:34.667  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
09-08 16:03:34.667  3865  3911 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,09-08 16:03:34.669  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:03:34.672  4238  4248 D BtGatt.GattService: registerClient() - UUID=03cb7421-6662-48b0-95b9-387a2b5c765b
,09-08 16:03:34.674  4238  4254 D BtGatt.GattService: onClientRegistered() - UUID=03cb7421-6662-48b0-95b9-387a2b5c765b, clientIf=5
,09-08 16:03:34.675  3865  3875 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,09-08 16:03:34.676  4238  4277 D BtGatt.GattService: start scan with filters
,09-08 16:03:34.681  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,09-08 16:03:34.681  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
09-08 16:03:34.681  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
09-08 16:03:34.681  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
09-08 16:03:34.681  4238  4257 D BtGatt.ScanManager: handling starting scan
,09-08 16:03:34.690  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,09-08 16:03:34.690  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
09-08 16:03:34.690  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,09-08 16:03:34.696  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,09-08 16:03:34.698  4238  4254 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,09-08 16:03:34.698  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:34.699  4238  4257 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,09-08 16:03:34.714  4238  4254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,09-08 16:03:34.714  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:34.715  4238  4257 D BtGatt.ScanManager: Starting BLE batch scan
,09-08 16:03:34.715  4238  4257 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,09-08 16:03:34.735  4238  4254 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,09-08 16:03:34.735  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:03:34.749  4238  4254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,09-08 16:03:34.749  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:03:35.114  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:03:35.190  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,09-08 16:03:35.191  3865  3865 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
09-08 16:03:35.191  3865  3865 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,09-08 16:03:36.252  4238  4238 D BtGatt.ScanManager: awakened up at time 433814
,09-08 16:03:36.254  4238  4257 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:03:36.293  4238  4254 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
09-08 16:03:36.293  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:36.293  4238  4254 D BtGatt.GattService: current time is 433855727945
09-08 16:03:36.294  4238  4254 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -97, 1, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121, 81, 34, 97, 112, -14, -5, 1, -128, -79, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 37, -47, 14, -113, 116, -46, 1, -128, -96, 17, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -83, 14, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -82, 12, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -82, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 107, 58, 19, -9, 93, -60, 1, -128, -103, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 0]
09-08 16:03:36.296  4238  4254 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 16:03:36.296  4238  4254 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
09-08 16:03:36.297  4238  4254 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74]
09-08 16:03:36.297  4238  4254 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
09-08 16:03:36.297  4238  4254 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
09-08 16:03:36.297  4238  4254 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9,, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
09-08 16:03:36.298  4238  4254 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
09-08 16:03:36.298  4238  4254 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107]
,09-08 16:03:37.712  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,09-08 16:03:37.713  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
09-08 16:03:37.713  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
09-08 16:03:37.713  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-08 16:03:37.714  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
09-08 16:03:37.714  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-08 16:03:37.714  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,09-08 16:03:37.715  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-08 16:03:37.715  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-08 16:03:37.716  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,09-08 16:03:37.716  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
09-08 16:03:37.718  3865  3911 D BluetoothAdapter: STATE_ON
,09-08 16:03:37.720  4238  4277 D BtGatt.GattService: stopScan() - queue size =1
09-08 16:03:37.723  4238  4249 D BtGatt.GattService: unregisterClient() - clientIf=5
,09-08 16:03:37.725  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-08 16:03:37.725  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,09-08 16:03:37.726  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,09-08 16:03:37.726  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,09-08 16:03:37.726  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,09-08 16:03:37.730  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
09-08 16:03:37.731  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
09-08 16:03:37.732  3865  3911 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-08 16:03:37.732  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-08 16:03:37.734  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:03:37.736  4238  4238 D BtGatt.ScanManager: awakened up at time 435297
,09-08 16:03:37.738  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:03:37.738  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:37.739  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.739  3865  3865 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-08 16:03:37.739  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-08 16:03:37.739  3865  3865 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false,
09-08 16:03:37.739  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:03:37.740  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@500042e removed from the list
09-08 16:03:37.740  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:37.740  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdbfbcf removed from the list
09-08 16:03:37.741  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:03:37.743  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
09-08 16:03:37.744  4238  4254 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
09-08 16:03:37.744  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.744  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:37.744  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-08 16:03:37.745  4238  4257 D BtGatt.ScanManager: stopping BLe Batch
,09-08 16:03:37.748  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:37.748  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
09-08 16:03:37.748  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-08 16:03:37.749  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdbfbcf not in the list
09-08 16:03:37.749  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.749  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:37.750  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:03:37.751  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:37.751  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:37.751  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@bdbfbcf not in the list
09-08 16:03:37.751  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:37.751  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.751  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:37.751  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@500042e not in the list
09-08 16:03:37.752  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-08 16:03:37.752  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@216cf48 added. We now have 3 listener(s)
09-08 16:03:37.754  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
09-08 16:03:37.754  4238  4254 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
09-08 16:03:37.754  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,09-08 16:03:37.754  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-08 16:03:37.754  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-08 16:03:37.754  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-08 16:03:37.754  4238  4257 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,09-08 16:03:37.756  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e61e1 added. We now have 4 listener(s)
09-08 16:03:37.756  3865  3911 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-08 16:03:37.756  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,09-08 16:03:37.759  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-08 16:03:37.765  3865  3911 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-08 16:03:37.767  3865  3911 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-08 16:03:37.768  3865  3911 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-08 16:03:37.769  3865  3911 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
09-08 16:03:37.769  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
09-08 16:03:37.769  3865  3911 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-08 16:03:37.769  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:37.769  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.770  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-08 16:03:37.770  3865  3911 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-08 16:03:37.770  3865  3911 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@216cf48 removed from the list
09-08 16:03:37.770  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:37.770  3865  3911 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e61e1 removed from the list
09-08 16:03:37.771  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-08 16:03:37.773  4238  4254 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,09-08 16:03:37.773  4238  4254 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
09-08 16:03:37.774  4238  4254 D BtGatt.GattService: current time is 435336039885
09-08 16:03:37.774  4238  4254 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -97, 1, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 16:03:37.774  4238  4254 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
09-08 16:03:37.774  3865  3865 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-08 16:03:37.774  3865  3911 D io.jxcore.node.ConnectivityMonitor: stop
09-08 16:03:37.775  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:37.776  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.776  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:37.778  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:37.778  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:03:37.779  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:37.779  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e61e1 not in the list
09-08 16:03:37.779  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.780  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:37.781  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,09-08 16:03:37.781  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
09-08 16:03:37.782  3865  3911 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-08 16:03:37.782  3865  3911 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8e61e1 not in the list
09-08 16:03:37.782  3865  3911 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-08 16:03:37.782  3865  3911 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-08 16:03:37.783  3865  3911 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-08 16:03:37.783  3865  3911 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@216cf48 not in the list
,09-08 16:03:37.785  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,09-08 16:03:37.786  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-08 16:03:37.786  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
09-08 16:03:37.787  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,09-08 16:03:37.787  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-08 16:03:37.787  3865  3911 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-08 16:03:38.241  3865  3865 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-08 16:03:39.809  3865  4334 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 458, name: My test thread name)
,09-08 16:03:41.806  3865  3911 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 458
,09-08 16:03:41.807  3865  3911 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 458, name: My test thread name)
,09-08 16:03:41.813  3865  4335 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: My test thread name)
,09-08 16:03:41.814  3865  4335 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 459, thread name: My test thread name)
09-08 16:03:41.814  3865  4335 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 459, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,09-08 16:03:41.820  3865  3911 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,09-08 16:03:41.828  3865  4336 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 463, name: My test thread name)
,09-08 16:03:41.831  3865  4334 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 458, name: My test thread name), during the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,09-08 16:03:41.829  3865  4336 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 463, thread name: My test thread name): Test exception.
,09-08 16:03:41.834  3865  4336 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 463, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,09-08 16:03:41.842  3865  3911 I jxcore-log: Total number of executed tests:  82
09-08 16:03:41.842  3865  3911 I jxcore-log: 
,09-08 16:03:41.844  3865  3911 I jxcore-log: Number of passed tests:  82
09-08 16:03:41.844  3865  3911 I jxcore-log: 
,09-08 16:03:41.845  3865  3911 I jxcore-log: Number of failed tests:  0
09-08 16:03:41.845  3865  3911 I jxcore-log: 
09-08 16:03:41.845  3865  3911 I jxcore-log: Number of ignored tests:  0
09-08 16:03:41.845  3865  3911 I jxcore-log: 
,09-08 16:03:41.846  3865  3911 I jxcore-log: Total duration:  101478
09-08 16:03:41.846  3865  3911 I jxcore-log: 
,09-08 16:03:41.855  3865  3911 I jxcore-log: Unit Test app is loaded
09-08 16:03:41.855  3865  3911 I jxcore-log: 
,09-08 16:03:41.870  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.870  3865  3911 I jxcore-log: 
,09-08 16:03:41.875  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.875  3865  3911 I jxcore-log: 
,09-08 16:03:41.876  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.876  3865  3911 I jxcore-log: 
09-08 16:03:41.877  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.877  3865  3911 I jxcore-log: 
,09-08 16:03:41.879  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 16:03:41.879  3865  3911 I jxcore-log: 
,09-08 16:03:41.880  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:03:41.880  3865  3911 I jxcore-log: 
,09-08 16:03:41.884  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.884  3865  3911 I jxcore-log: 
,09-08 16:03:41.886  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.886  3865  3911 I jxcore-log: 
,09-08 16:03:41.887  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 16:03:41.887  3865  3911 I jxcore-log: 
,09-08 16:03:41.888  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:03:41.888  3865  3911 I jxcore-log: 
09-08 16:03:41.889  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:03:41.889  3865  3911 I jxcore-log: 
,09-08 16:03:41.889  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.889  3865  3911 I jxcore-log: 
,09-08 16:03:41.890  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.890  3865  3911 I jxcore-log: 
09-08 16:03:41.890  3865  3865 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-08 16:03:41.891  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.891  3865  3911 I jxcore-log: 
09-08 16:03:41.892  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.892  3865  3911 I jxcore-log: 
09-08 16:03:41.893  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.893  3865  3911 I jxcore-log: 
,09-08 16:03:41.894  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.894  3865  3911 I jxcore-log: 
09-08 16:03:41.895  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.895  3865  3911 I jxcore-log: 
,09-08 16:03:41.896  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.896  3865  3911 I jxcore-log: 
,09-08 16:03:41.897  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.897  3865  3911 I jxcore-log: 
,09-08 16:03:41.898  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.898  3865  3911 I jxcore-log: 
,09-08 16:03:41.899  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.899  3865  3911 I jxcore-log: 
09-08 16:03:41.900  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.900  3865  3911 I jxcore-log: 
,09-08 16:03:41.901  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.901  3865  3911 I jxcore-log: 
,09-08 16:03:41.902  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.902  3865  3911 I jxcore-log: 
,09-08 16:03:41.902  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.902  3865  3911 I jxcore-log: 
09-08 16:03:41.903  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.903  3865  3911 I jxcore-log: 
,09-08 16:03:41.904  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.904  3865  3911 I jxcore-log: 
,09-08 16:03:41.906  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.906  3865  3911 I jxcore-log: 
,09-08 16:03:41.906  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.906  3865  3911 I jxcore-log: 
09-08 16:03:41.907  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.907  3865  3911 I jxcore-log: 
,09-08 16:03:41.907  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.907  3865  3911 I jxcore-log: 
,09-08 16:03:41.908  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.908  3865  3911 I jxcore-log: 
,09-08 16:03:41.908  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.908  3865  3911 I jxcore-log: 
09-08 16:03:41.909  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.909  3865  3911 I jxcore-log: 
09-08 16:03:41.909  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.909  3865  3911 I jxcore-log: 
,09-08 16:03:41.910  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.910  3865  3911 I jxcore-log: 
09-08 16:03:41.910  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.910  3865  3911 I jxcore-log: 
09-08 16:03:41.911  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.911  3865  3911 I jxcore-log: 
,09-08 16:03:41.911  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.911  3865  3911 I jxcore-log: 
09-08 16:03:41.912  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
09-08 16:03:41.912  3865  3911 I jxcore-log: 
,09-08 16:03:41.912  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.912  3865  3911 I jxcore-log: 
09-08 16:03:41.913  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
09-08 16:03:41.913  3865  3911 I jxcore-log: 
09-08 16:03:41.913  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.913  3865  3911 I jxcore-log: 
09-08 16:03:41.914  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.914  3865  3911 I jxcore-log: 
,09-08 16:03:41.914  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.914  3865  3911 I jxcore-log: 
09-08 16:03:41.915  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.915  3865  3911 I jxcore-log: 
,09-08 16:03:41.915  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.915  3865  3911 I jxcore-log: 
,09-08 16:03:41.916  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:03:41.916  3865  3911 I jxcore-log: 
,09-08 16:03:41.916  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.916  3865  3911 I jxcore-log: 
,09-08 16:03:41.917  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}
09-08 16:03:41.917  3865  3911 I jxcore-log: 
,09-08 16:03:41.917  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.917  3865  3911 I jxcore-log: 
,09-08 16:03:41.918  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:03:41.918  3865  3911 I jxcore-log: 
,09-08 16:03:41.918  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
09-08 16:03:41.918  3865  3911 I jxcore-log: 
,09-08 16:03:41.918  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-08 16:03:41.918  3865  3911 I jxcore-log: 
09-08 16:03:41.919  3865  3911 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-08 16:03:41.919  3865  3911 I jxcore-log: 
09-08 16:03:41.921  3865  3911 I jxcore-log: My device name is: motorola-Nexus 6
09-08 16:03:41.921  3865  3911 I jxcore-log: 
09-08 16:03:41.922  3865  3911 I jxcore-log: WARN testUtils: myNameCallback not set!
09-08 16:03:41.922  3865  3911 I jxcore-log: 
,09-08 16:03:41.922  3865  3911 I jxcore-log: Running for WIFI network type
09-08 16:03:41.922  3865  3911 I jxcore-log: 
,09-08 16:03:44.407  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
09-08 16:03:44.407  3865  3911 I jxcore-log: 
,09-08 16:03:44.868  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
09-08 16:03:44.868  3865  3911 I jxcore-log: 
,09-08 16:03:44.902  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
09-08 16:03:44.902  3865  3911 I jxcore-log: 
,09-08 16:03:46.300  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
09-08 16:03:46.300  3865  3911 I jxcore-log: 
,09-08 16:03:46.547  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
09-08 16:03:46.547  3865  3911 I jxcore-log: 
,09-08 16:03:46.552  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
09-08 16:03:46.552  3865  3911 I jxcore-log: 
,09-08 16:03:46.559  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js
09-08 16:03:46.559  3865  3911 I jxcore-log: 
,09-08 16:03:46.826  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
09-08 16:03:46.826  3865  3911 I jxcore-log: 
,09-08 16:03:46.843  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
09-08 16:03:46.843  3865  3911 I jxcore-log: 
,09-08 16:03:46.847  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js
09-08 16:03:46.847  3865  3911 I jxcore-log: 
,09-08 16:03:47.572  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js
09-08 16:03:47.572  3865  3911 I jxcore-log: 
,09-08 16:03:47.742  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
09-08 16:03:47.742  3865  3911 I jxcore-log: 
,09-08 16:03:48.081  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
09-08 16:03:48.081  3865  3911 I jxcore-log: 
,09-08 16:03:48.092  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
09-08 16:03:48.092  3865  3911 I jxcore-log: 
,09-08 16:03:48.099  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
09-08 16:03:48.099  3865  3911 I jxcore-log: 
,09-08 16:03:48.106  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
09-08 16:03:48.106  3865  3911 I jxcore-log: 
,09-08 16:03:48.148  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
09-08 16:03:48.148  3865  3911 I jxcore-log: 
,09-08 16:03:48.196  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
09-08 16:03:48.196  3865  3911 I jxcore-log: 
,09-08 16:03:48.203  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
09-08 16:03:48.203  3865  3911 I jxcore-log: 
,09-08 16:03:48.211  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
09-08 16:03:48.211  3865  3911 I jxcore-log: 
,09-08 16:03:48.232  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
09-08 16:03:48.232  3865  3911 I jxcore-log: 
,09-08 16:03:48.237  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
09-08 16:03:48.237  3865  3911 I jxcore-log: 
,09-08 16:03:48.243  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
09-08 16:03:48.243  3865  3911 I jxcore-log: 
,09-08 16:03:48.260  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
09-08 16:03:48.260  3865  3911 I jxcore-log: 
,09-08 16:03:48.287  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
09-08 16:03:48.287  3865  3911 I jxcore-log: 
,09-08 16:03:48.298  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
09-08 16:03:48.298  3865  3911 I jxcore-log: 
,09-08 16:03:48.312  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
09-08 16:03:48.312  3865  3911 I jxcore-log: 
,09-08 16:03:48.324  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
09-08 16:03:48.324  3865  3911 I jxcore-log: 
,09-08 16:03:48.340  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
09-08 16:03:48.340  3865  3911 I jxcore-log: 
,09-08 16:03:48.351  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
09-08 16:03:48.351  3865  3911 I jxcore-log: 
,09-08 16:03:48.357  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
09-08 16:03:48.357  3865  3911 I jxcore-log: 
,09-08 16:03:48.388  3865  3911 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
09-08 16:03:48.388  3865  3911 I jxcore-log: 
,09-08 16:03:48.400  3865  3911 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,09-08 16:03:48.401  3865  3911 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
09-08 16:03:48.401  3865  3911 I jxcore-log: 
,09-08 16:03:48.404  3865  3911 I jxcore-log: ThaliTestRunner :: Running ThaliTape
09-08 16:03:48.404  3865  3911 I jxcore-log: 
,09-08 16:03:48.404  3865  3911 I jxcore-log: ThaliTape :: Started ThaliTape
09-08 16:03:48.404  3865  3911 I jxcore-log: 
,09-08 16:03:48.409  3865  3911 I jxcore-log: ThaliTape ::  Connecting to  http://85.14.110.168:3000/
09-08 16:03:48.409  3865  3911 I jxcore-log: 
,09-08 16:03:48.582  3865  3911 I jxcore-log: ThaliTape :: Connected to the test server
09-08 16:03:48.582  3865  3911 I jxcore-log: 
,09-08 16:04:36.986  3026  4349 V KeepSync: Connecting to GoogleApiClient
09-08 16:04:36.987   876  1997 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 16:04:37.059  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:04:37.062  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:04:37.098  1527  2184 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 16:04:37.098  1527  2184 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 16:04:37.098  1527  2184 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:04:37.098  1527  2184 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:04:37.112  1766  4350 V BaseAuthAsyncOperation: access token request failed
,09-08 16:04:37.113  3026  4349 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 16:04:37.154  1527  2321 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 16:04:37.155  1527  2321 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 16:04:37.155  1527  2321 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 16:04:37.155  1527  2321 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:04:37.169  3026  4349 E KeepSync: IOException
09-08 16:04:37.169  3026  4349 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 16:04:37.169  3026  4349 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:04:37.169  3026  4349 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 16:04:37.169  3026  4349 E KeepSync: 	... 10 more
09-08 16:04:37.169  3026  4349 W KeepSync: Sync result 2
,09-08 16:04:37.175   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 494292, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:05:09.885  3749  4353 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 16:05:09.920  3749  4354 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 16:05:09.928  3026  4352 V KeepSync: Connecting to GoogleApiClient
,09-08 16:05:09.932   876  1997 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 16:05:09.946  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:05:09.952  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:05:10.041  1527  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 16:05:10.041  1527  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 16:05:10.041  1527  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:05:10.041  1527  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:05:10.055  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 16:05:10.056  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
09-08 16:05:10.056  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:05:10.056  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:05:10.130  1766  4355 V BaseAuthAsyncOperation: access token request failed
,09-08 16:05:10.131  3026  4352 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 16:05:10.157  1527  2972 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
09-08 16:05:10.157  1527  2972 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 16:05:10.157  1527  2972 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:05:10.157  1527  2972 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:05:10.176  3749  4354 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 16:05:10.177  3749  4353 E BooksSync: Soft error
09-08 16:05:10.177  3749  4353 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 16:05:10.177  3749  4353 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 16:05:10.177  3749  4353 E BooksSync: Sync error
09-08 16:05:10.177  3749  4353 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 16:05:10.177  3749  4353 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
09-08 16:05:10.177  3749  4353 I BooksSync: Finished books sync
,09-08 16:05:10.180   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 527393, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:05:10.226  1527  2362 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
09-08 16:05:10.226  1527  2362 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 16:05:10.226  1527  2362 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 16:05:10.227  1527  2362 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:05:10.239  3026  4352 E KeepSync: IOException
09-08 16:05:10.239  3026  4352 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 16:05:10.239  3026  4352 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:05:10.239  3026  4352 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 16:05:10.239  3026  4352 E KeepSync: 	... 10 more
09-08 16:05:10.239  3026  4352 W KeepSync: Sync result 2
,09-08 16:05:10.275   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 527326, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:05:40.984  3749  4357 I BooksSync: Starting books sync for 61035162, extras: ade
,09-08 16:05:41.004  3749  4358 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,09-08 16:05:41.017  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:05:41.019  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:05:41.055  1527  2321 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 16:05:41.055  1527  2321 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
09-08 16:05:41.055  1527  2321 I GLSUser : [GLSUser] Extracting token using key: Auth
,09-08 16:05:41.055  1527  2321 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:05:41.085  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:05:41.086  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:05:41.112  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,09-08 16:05:41.112  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,09-08 16:05:41.112  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:05:41.113  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:05:41.131  3749  4358 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,09-08 16:05:41.136  3749  4357 E BooksSync: Soft error
09-08 16:05:41.136  3749  4357 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 16:05:41.136  3749  4357 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 16:05:41.136  3749  4357 E BooksSync: Sync error
09-08 16:05:41.136  3749  4357 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
09-08 16:05:41.136  3749  4357 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,09-08 16:05:41.136  3749  4357 I BooksSync: Finished books sync
,09-08 16:05:41.138   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 558485, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:06:11.543  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:06:11.545  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:06:11.592  1527  2972 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
09-08 16:06:11.593  1527  2972 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 16:06:11.593  1527  2972 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:06:11.593  1527  2972 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:06:11.610  3550  4362 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
09-08 16:06:11.610  3550  4362 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jdm.a(PG:82)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jcs.o(PG:406)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jcn.a(PG:1379)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jcs.i(PG:143)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at blb.a(PG:3937)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at czp.a(PG:18188)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at czp.a(PG:9081)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at czq.run(PG:1686)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:06:11.610  3550  4362 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jdj.a(PG:4091)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jdj.a(PG:1125)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jdm.a(PG:77)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	... 12 more
09-08 16:06:11.610  3550  4362 E HttpOperation: Caused by: faj: BadAuthentication
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at fal.a(PG:38)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	at jdj.a(PG:4089)
09-08 16:06:11.610  3550  4362 E HttpOperation: 	... 14 more
,09-08 16:06:11.641  1527  2184 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,09-08 16:06:11.641  1527  2184 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
09-08 16:06:11.641  1527  2184 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:06:11.641  1527  2184 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:06:11.657  3550  4362 E HttpOperation: [getmobileexperiments] Unexpected exception
09-08 16:06:11.657  3550  4362 E HttpOperation: java.io.IOException: Cannot obtain authentication token
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jdm.a(PG:82)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jcs.o(PG:406)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jcn.a(PG:1379)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jcs.i(PG:143)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at hec.a(PG:42)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at hee.a(PG:102)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at czr.a(PG:65)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at kka.a(PG:108)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at czp.a(PG:19176)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at czp.a(PG:9081)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at czq.run(PG:1686)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:06:11.657  3550  4362 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jdj.a(PG:4091)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jdj.a(PG:1125)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jdm.a(PG:77)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	... 15 more
09-08 16:06:11.657  3550  4362 E HttpOperation: Caused by: faj: BadAuthentication
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at fal.a(PG:38)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	at jdj.a(PG:4089)
09-08 16:06:11.657  3550  4362 E HttpOperation: 	... 17 more
09-08 16:06:11.658  3550  4362 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
09-08 16:06:11.658  3550  4362 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jdm.a(PG:82)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jcs.o(PG:406)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jcn.a(PG:1379)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jcs.i(PG:143)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at hec.a(PG:42)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at hee.a(PG:102)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at czr.a(PG:65)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at kka.a(PG:108)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at czp.a(PG:19176)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at czp.a(PG:9081)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at czq.run(PG:1686)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jdj.a(PG:4091)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jdj.a(PG:1,125)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jdm.a(PG:77)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	... 15 more
09-08 16:06:11.658  3550  4362 E ExperimentLoader: Caused by: faj: BadAuthentication
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at fal.a(PG:38)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	at jdj.a(PG:4089)
09-08 16:06:11.658  3550  4362 E ExperimentLoader: 	... 17 more
,09-08 16:06:11.812   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 584062, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:06:42.056  3026  4365 V KeepSync: Connecting to GoogleApiClient
,09-08 16:06:42.057   876  1997 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,09-08 16:06:42.124  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:06:42.126  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,09-08 16:06:42.175  1527  1538 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
09-08 16:06:42.175  1527  1538 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,09-08 16:06:42.175  1527  1538 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:06:42.176  1527  1538 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:06:42.212  1766  4366 V BaseAuthAsyncOperation: access token request failed
,09-08 16:06:42.214  3026  4365 V KeepSync: GoogleApiClient failed to connect with error code: 4
,09-08 16:06:42.302  1527  1539 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,09-08 16:06:42.302  1527  1539 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
09-08 16:06:42.302  1527  1539 I GLSUser : [GLSUser] Extracting token using key: Auth
09-08 16:06:42.302  1527  1539 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,09-08 16:06:42.328  3026  4365 E KeepSync: IOException
09-08 16:06:42.328  3026  4365 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
09-08 16:06:42.328  3026  4365 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
09-08 16:06:42.328  3026  4365 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
09-08 16:06:42.328  3026  4365 E KeepSync: 	... 10 more
,09-08 16:06:42.328  3026  4365 W KeepSync: Sync result 2
,09-08 16:06:42.341   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 593015, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,09-08 16:11:10.809   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=888370, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:11:24.836   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=902397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:11:35.876   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=913437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:11:49.902   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=927463, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:12:00.969   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=938530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:12:14.982   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=952543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:12:26.035   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=963597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:12:40.035   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=977597, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:12:51.102   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=988663, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:13:05.116   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1002677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:13:16.169   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1013730, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:13:30.182   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1027744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:13:41.209   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1038771, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:13:55.235   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1052796, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:14:06.302   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1063863, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:14:20.315   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1077877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:14:31.422   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1088984, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:14:45.435   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1102997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:14:56.489   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1114050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:15:10.502   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1128064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:15:21.555   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1139117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:15:35.569   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1153130, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:15:46.622   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1164183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:16:00.622   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1178183, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:16:11.716   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1189277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:16:25.716   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1203277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:16:28.296   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1205857, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:16:41.235   876   888 I UsageStatsService: User[0] Flushing usage stats to disk
,09-08 16:16:50.768   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1228330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:16:53.362   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1230923, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:17:15.849   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1253410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:17:18.435   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1255997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:17:40.902   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1278464, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:17:43.489   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1281050, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:18:05.969   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1303530, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:18:08.555   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1306117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:18:31.049   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1328610, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:18:33.648   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1331210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:18:56.116   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1353677, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:18:58.709   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1356270, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:19:21.182   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1378744, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:19:23.769   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1381330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:19:46.249   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1403810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:19:48.835   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1406397, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:20:11.316   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1428877, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:20:13.915   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1431476, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:20:36.395   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1453957, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:20:38.982   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1456543, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:21:01.462   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1479024, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:21:07.008   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1484570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:21:26.516   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1504077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:21:32.089   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1509650, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:21:51.582   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1529144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:21:57.182   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1534743, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:22:16.675   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1554237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:22:22.262   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1559823, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:22:41.796   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1579357, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:22:47.342   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1584903, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:23:06.862   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1604423, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:23:14.355   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1611917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:23:33.876   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1631437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:23:39.448   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1637010, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:23:58.955   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1656517, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:24:04.515   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1662077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:24:24.022   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1681583, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:24:29.582   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1687143, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:24:49.075   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1706637, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,09-08 16:24:54.635   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1712196, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,09-08 16:25:14.142   876  4294 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1731704, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,TIME-OUT KILL (timeout was 1400000ms),09-08 16:25:14.949  4424  4424 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
09-08 16:25:14.953  4424  4424 D AndroidRuntime: CheckJNI is OFF
09-08 16:25:14.989  4424  4424 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
09-08 16:25:15.027  4424  4424 I Radio-JNI: register_android_hardware_Radio DONE
09-08 16:25:15.047  4424  4424 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-08 16:25:15.059   876   889 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
09-08 16:25:15.060   876   889 I ActivityManager: Killing 3865:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
09-08 16:25:15.173   876   899 W PackageSettings: Skipping PackageSetting{a3391b9 com.example.hello/10273} due to missing metadata
09-08 16:25:15.204   876  1384 I WindowState: WIN DEATH: Window{2eb4558 u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-08 16:25:15.204   876  1317 D WifiService: Client connection lost with reason: 4
09-08 16:25:15.206   876  2016 D GraphicsStats: Buffer count: 2
09-08 16:25:15.229   876   899 I art     : Starting a blocking GC Explicit
09-08 16:25:15.245   876   889 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
09-08 16:25:15.246   876   889 W PackageManager: Package com.test.thalitest is missing; assuming frozen
09-08 16:25:15.247   876   889 E ActivityManager: Failure starting process com.test.thalitest
09-08 16:25:15.247   876   889 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
09-08 16:25:15.247   876   889 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.247   876   889 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.247   876   889 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.247   876   889 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 16:25:15.249   876   889 I ActivityManager:   Force finishing activity ActivityRecord{856540d u0 com.test.thalitest/.MainActivity t4}
09-08 16:25:15.258   876  3160 W ActivityManager: Spurious death for ProcessRecord{859362b 0:com.test.thalitest/u0a0}, curProc for 3865: null
09-08 16:25:15.284   876   899 I art     : Explicit concurrent mark sweep GC freed 79594(5MB) AllocSpace objects, 10(200KB) LOS objects, 33% free, 29MB/43MB, paused 730us total 54.745ms
09-08 16:25:15.305   876   899 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
09-08 16:25:15.308  4424  4424 I art     : System.exit called, status: 0
09-08 16:25:15.308  4424  4424 I AndroidRuntime: VM exiting with result code 0.
09-08 16:25:15.313   876   899 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
09-08 16:25:15.328   876   889 I ActivityManager: Exiting empty application process com.test.thalitest (null)
09-08 16:25:15.331  4238  4238 D BluetoothMapAppObserver: onReceive
09-08 16:25:15.331  4238  4238 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
09-08 16:25:15.332  2188  2316 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-08 16:25:15.342  3636  3636 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
09-08 16:25:15.343   876  1308 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-08 16:25:15.347  1910  1910 I Keyboard.Facilitator: resetDictionaries() : en_US
09-08 16:25:15.368  1910  4438 I Keyboard.Facilitator.DecoderInitializer: run()
09-08 16:25:15.384   876  1543 I ActivityManager: Start proc 4441:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
09-08 16:25:15.386  1973  1973 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
09-08 16:25:15.389  1910  4438 I Decoder : createOrResetDecoder
09-08 16:25:15.406  1527  1527 I ConfigService: onCreate
09-08 16:25:15.419  4441  4441 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
09-08 16:25:15.436  1910  4438 I Keyboard.Facilitator.MainLanguageModelLoader: run()
09-08 16:25:15.439   876   876 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-08 16:25:15.449   876  1997 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3865 uid 10000
09-08 16:25:15.451  1910  1910 I Keyboard.Facilitator: onFinishInput()
09-08 16:25:15.457  1990  2070 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
09-08 16:25:15.458   876   888 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
09-08 16:25:15.459   876   888 E PackageManager: Failed to write settings, restoring backup
09-08 16:25:15.459   876   888 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
09-08 16:25:15.459   876   888 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
09-08 16:25:15.459   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
09-08 16:25:15.459   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
09-08 16:25:15.459   876   888 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
09-08 16:25:15.459   876   888 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.459   876   888 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.459   876   888 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.463   876   889 E DropBoxManagerService: Can't write: system_server_wtf
09-08 16:25:15.463   876   889 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
09-08 16:25:15.463   876   889 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:25:15.463   876   889 E DropBoxManagerService: 	... 13 more
09-08 16:25:15.464  1910  4438 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
09-08 16:25:15.465  1910  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
09-08 16:25:15.465  1910  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
09-08 16:25:15.467  1910  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
09-08 16:25:15.467  1910  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
09-08 16:25:15.467  1910  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
09-08 16:25:15.467  1910  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
09-08 16:25:15.468  1910  4438 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
09-08 16:25:15.468  1910  4438 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
09-08 16:25:15.468  1910  4438 I Keyboard.Facilitator.Delight2FileSweeper: run()
09-08 16:25:15.468  1910  4438 I Keyboard.Facilitator.RecurringTaskScheduler: run()
09-08 16:25:15.468  1910  4438 I StatsUtilsManager: startPeriodStatsRecorder() : Success
09-08 16:25:15.468  1910  4438 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
09-08 16:25:15.470   876   887 I ActivityManager: Start proc 4458:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
09-08 16:25:15.471  1990  2070 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
09-08 16:25:15.471  1990  2070 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1990
09-08 16:25:15.471  1990  2070 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.471  1990  2070 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.473   876  1931 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 16:25:15.473   876  4463 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:25:15.473   876  4463 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop124.tmp: open failed: EROFS (Read-only file system)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:25:15.473   876  4463 E DropBoxManagerService: 	... 5 more
09-08 16:25:15.476  1990  2070 I Process : Sending signal. PID: 1990 SIG: 9
09-08 16:25:15.490  4441  4441 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
09-08 16:25:15.509   876  2016 I ActivityManager: Start proc 4472:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
09-08 16:25:15.510  4441  4475 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
09-08 16:25:15.543  4472  4472 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.555  4441  4457 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.555  4441  4457 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.564  1527  1527 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
09-08 16:25:15.565  1527  1527 D AndroidRuntime: Shutting down VM
09-08 16:25:15.566  1527  1527 E AndroidRuntime: FATAL EXCEPTION: main
09-08 16:25:15.566  1527  1527 E AndroidRuntime: Process: com.google.process.gapps, PID: 1527
09-08 16:25:15.566  1527  1527 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
09-08 16:25:15.566  1527  1527 E AndroidRuntime: 	... 8 more
09-08 16:25:15.569   876  4489 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:25:15.569   876  4489 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:25:15.569   876  4489 E DropBoxManagerService: 	... 5 more
09-08 16:25:15.569  1527  1527 I Process : Sending signal. PID: 1527 SIG: 9
09-08 16:25:15.595   876  1307 W InputDispatcher: channel '240012e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
09-08 16:25:15.595   876  1307 E InputDispatcher: channel '240012e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
09-08 16:25:15.596   876  1931 D GraphicsStats: Buffer count: 1
09-08 16:25:15.596   876   886 I WindowState: WIN DEATH: Window{240012e u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
09-08 16:25:15.600   876   886 W InputDispatcher: Attempted to unregister already unregistered input channel '240012e com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
09-08 16:25:15.607   876  1931 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1990) has died
09-08 16:25:15.607   876  1931 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
09-08 16:25:15.608   876  1931 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
09-08 16:25:15.617   876  1997 I ActivityManager: Killing 3690:com.google.android.apps.docs/u0a46 (adj 15): empty #17
09-08 16:25:15.629   876  1317 D WifiService: Client connection lost with reason: 4
09-08 16:25:15.651  4441  4457 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.656  4441  4475 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
09-08 16:25:15.656  4441  4475 E AndroidRuntime: Process: android.process.acore, PID: 4441
09-08 16:25:15.656  4441  4475 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.656  4441  4475 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
09-08 16:25:15.657  4441  4457 I Process : Sending signal. PID: 4441 SIG: 9
09-08 16:25:15.675   876   889 I ActivityManager: Start proc 4492:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 16:25:15.675   876   886 I ActivityManager: Process com.google.process.gapps (pid 1527) has died
09-08 16:25:15.675   876   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 1000ms
09-08 16:25:15.675   876   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
09-08 16:25:15.676   876   886 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 21000ms
09-08 16:25:15.680   876  4497 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:25:15.680   876  4497 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:25:15.680   876  4497 E DropBoxManagerService: 	... 5 more
09-08 16:25:15.698  1766  1766 W RocketImpressions: ClearcutLogger connection suspended: 1
09-08 16:25:15.698   876  1931 I ActivityManager: Start proc 4503:com.google.process.gapps/u0a11 for content provider com.google.android.gsf/.gservices.GservicesProvider
09-08 16:25:15.726   876  1999 I ActivityManager: Process android.process.acore (pid 4441) has died
09-08 16:25:15.726   876  1999 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
09-08 16:25:15.742  4503  4503 W System  : ClassLoader referenced unknown path: /system/priv-app/GoogleServicesFramework/lib/arm
09-08 16:25:15.749  4503  4503 I GservicesProvider: Gservices pushing to system: true; secure/global: true
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:25:15.751  4492  4492 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:25:15.751  4492  4492 D AndroidRuntime: Shutting down VM
09-08 16:25:15.753  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-08 16:25:15.754  1766  1766 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gsf/databases/gservices.db'.
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:25:15.759  4503  4503 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:25:15.759  4503  4503 D AndroidRuntime: Shutting down VM
09-08 16:25:15.759  1766  1766 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
09-08 16:25:15.759  1766  1766 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
09-08 16:25:15.761  4492  4492 E AndroidRuntime: FATAL EXCEPTION: main
09-08 16:25:15.761  4492  4492 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4492
09-08 16:25:15.761  4492  4492 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 16:25:15.761  4492  4492 E AndroidRuntime: 	... 10 more
09-08 16:25:15.761  4503  4503 E AndroidRuntime: FATAL EXCEPTION: main
09-08 16:25:15.761  4503  4503 E AndroidRuntime: Process: com.google.process.gapps, PID: 4503
09-08 16:25:15.761  4503  4503 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.google.android.gsf.gservices.GservicesProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.computeLocalDigestAndUpdateValues(GservicesProvider.java:450)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at com.google.android.gsf.gservices.GservicesProvider.onCreate(GservicesProvider.java:185)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
09-08 16:25:15.761  4503  4503 E AndroidRuntime: 	... 10 more
09-08 16:25:15.768   876   886 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
09-08 16:25:15.768   876  4520 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:25:15.768   876  4520 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:25:15.768   876  4520 E DropBoxManagerService: 	... 5 more
09-08 16:25:15.769   876  4521 E DropBoxManagerService: Can't write: system_app_crash
09-08 16:25:15.769   876  4521 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
09-08 16:25:15.769   876  4521 E DropBoxManagerService: 	... 5 more
09-08 16:25:15.770  4492  4492 I Process : Sending signal. PID: 4492 SIG: 9
09-08 16:25:15.772  4503  4503 I Process : Sending signal. PID: 4503 SIG: 9
09-08 16:25:15.785  1766  4519 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
09-08 16:25:15.789   876  3160 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
09-08 16:25:15.790   876  3160 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
09-08 16:25:15.790   876  3160 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17118)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2483)
09-08 16:25:15.790   876  3160 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
09-08 16:25:15.801  1766  4519 E AndroidRuntime: Process: com.google.android.gms, PID: 1766
09-08 16:25:15.801  1766  4519 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
09-08 16:25:15.801  1766  4519 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)

```
