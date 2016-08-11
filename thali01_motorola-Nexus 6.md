#### Test 807613742dabe25_thali01_motorola-Nexus 6 Logs


```
--------- beginning of system
08-11 12:30:27.926   873   873 I ActivityManager: Start proc 3989:com.google.android.deskclock/u0a44 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,--------- beginning of main
08-11 12:30:28.011  3989  3989 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm
08-11 12:30:28.095  3989  3989 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-11 12:30:28.095  3989  3989 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 12:30:28.095  3989  3989 I GAv4    :   adb logcat -s GAv4
08-11 12:30:28.111  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 12:30:28.112  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 12:30:28.131  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-11 12:30:28.131  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 12:30:28.131  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:30:28.131  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 12:30:28.142  3580  4004 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:30:28.142  3580  4004 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:30:28.142  3580  4004 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	... 12 more
08-11 12:30:28.142  3580  4004 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at fal.a(PG:38)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:30:28.142  3580  4004 E HttpOperation: 	... 14 more
08-11 12:30:28.166  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-11 12:30:28.166  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 12:30:28.166  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:30:28.166  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-11 12:30:28.178  3580  4004 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:30:28.178  3580  4004 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at hec.a(PG:42)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at hee.a(PG:102)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at czr.a(PG:65)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at kka.a(PG:108)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:30:28.178  3580  4004 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	... 15 more
08-11 12:30:28.178  3580  4004 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at fal.a(PG:38)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:30:28.178  3580  4004 E HttpOperation: 	... 17 more
08-11 12:30:28.178  3580  4004 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:30:28.178  3580  4004 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	... 15 more
08-11 12:30:28.178  3580  4004 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 12:30:28.178  3580  4004 E ExperimentLoader: 	... 17 more
08-11 12:30:28.220  3989  3989 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-11 12:30:28.238  3989  3989 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-11 12:30:28.297   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 290197, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
08-11 12:30:28.298   873  1771 I ActivityManager: Killing 3593:com.google.process.gapps/u0a99 (adj 15): empty #17
08-11 12:30:28.314  3989  4008 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-11 12:30:28.588  4001  4001 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 12:30:28.593  4001  4001 D AndroidRuntime: CheckJNI is OFF
08-11 12:30:28.628  4001  4001 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 12:30:28.670  4001  4001 I Radio-JNI: register_android_hardware_Radio DONE
08-11 12:30:28.690  4001  4001 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 12:30:28.698   873   884 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 12:30:28.751   873   884 I ActivityManager: Start proc 4017:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-11 12:30:28.754  4001  4001 D AndroidRuntime: Shutting down VM
08-11 12:30:28.867  4017  4017 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-11 12:30:28.897  4017  4017 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-11 12:30:28.903  4017  4017 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2121-2123)
08-11 12:30:28.903  4017  4017 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:30:28.919  4017  4017 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {f678e70}
08-11 12:30:28.919  4017  4017 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:30:28.919  4017  4017 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 12:30:28.926  4017  4017 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 12:30:28.927  4017  4017 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 12:30:28.969  4017  4017 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 12:30:28.986  4017  4017 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:30:28.986  4017  4017 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:30:28.986  4017  4017 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 12:30:28.986  4017  4017 I Adreno  : Build Date                       : 10/20/15
08-11 12:30:28.986  4017  4017 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 12:30:28.986  4017  4017 I Adreno  : Local Branch                     : M14
08-11 12:30:28.986  4017  4017 I Adreno  : Remote Branch                    : 
08-11 12:30:28.986  4017  4017 I Adreno  : Remote Branch                    : 
08-11 12:30:28.986  4017  4017 I Adreno  : Reconstruct Branch               : 
,08-11 12:30:29.054   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@32d9651:true
,08-11 12:30:29.095  4017  4017 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 12:30:29.113  4017  4017 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-11 12:30:29.212  4017  4054 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-11 12:30:29.239  4017  4041 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-11 12:30:29.269  4017  4054 I OpenGLRenderer: Initialized EGL, version 1.4
,08-11 12:30:29.287  1650  1650 I Keyboard.Facilitator: onFinishInput()
,08-11 12:30:29.345   873   891 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +527ms (total +614ms)
,08-11 12:30:29.413  4017  4017 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4017
,08-11 12:30:29.531  4017  4017 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 12:30:29.685  4017  4055 D jxcore_app_log: JniHelper::setJavaVM(0xb4d7c000), pthread_self() = -1658848976
,08-11 12:30:29.694  4017  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 12:30:29.694  4017  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 12:30:29.694  4017  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 12:30:29.694  4017  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 12:30:29.694  4017  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 12:30:29.694  4017  4055 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b1a2ac7 added. We now have 1 listener(s)
,08-11 12:30:29.699  4017  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-11 12:30:29.700  4017  4055 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 12:30:29.701  4017  4055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 12:30:29.701  4017  4055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: ,
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 12:30:29.706  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 12:30:29.707  4017  4055 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b198a92 added. We now have 1 listener(s)
08-11 12:30:29.707  4017  4055 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:30:29.713   873  1305 D WifiService: New client listening to asynchronous messages
,08-11 12:30:29.715  4017  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:30:29.715  4017  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 12:30:29.715  4017  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 12:30:29.716  4017  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 12:30:29.716  4017  4055 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 12:30:29.718  4017  4055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:30:29.718  4017  4055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-11 12:30:29.738  4017  4055 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:30:29.739  4017  4055 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:30:29.739  4017  4055 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 12:30:29.739  4017  4055 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:30:29.739  4017  4055 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 12:30:29.741  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:29.744  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:29.761  4017  4017 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 12:30:30.721  4017  4063 W jxcore-log: Initializing JXcore engine
08-11 12:30:30.721  4017  4063 W jxcore-log: JXcore engine is ready
08-11 12:30:30.757  4063  4063 W Thread-365: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8947 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-11 12:30:30.760  4063  4063 W Thread-365: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10619]" dev="sockfs" ino=10619 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 12:30:30.760  4063  4063 W Thread-365: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 12:30:30.760  4063  4063 W Thread-365: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[27026]" dev="sockfs" ino=27026 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 12:30:30.775  4017  4063 W jxcore-log: Starting JXcore engine
08-11 12:30:30.853  4017  4063 W jxcore-log: Platform android
08-11 12:30:30.853  4017  4063 W jxcore-log: 
08-11 12:30:30.853  4017  4063 W jxcore-log: Process ARCH arm
08-11 12:30:30.853  4017  4063 W jxcore-log: 
08-11 12:30:31.077  4017  4063 I jxcore-log: JXcore Cordova bridge is ready!
08-11 12:30:31.077  4017  4063 I jxcore-log: 
08-11 12:30:31.078  4017  4063 W jxcore-log: JXcore engine is started
08-11 12:30:31.088  4017  4055 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 12:30:31.092  4017  4017 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-11 12:30:39.157  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:30:39.160  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:30:39.171  3899  4065 V GoogleAuthProtoRequest: [348] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 12:30:39.212  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-11 12:30:39.212  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 12:30:39.212  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:30:39.212  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: [348] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: [348] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 12:30:39.235  3899  4065 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 12:30:43.470   873  2139 D NetlinkSocketObserver: NeighborEvent{elapsedMs=326690, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 12:30:46.523  4017  4063 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 12:30:46.523  4017  4063 I jxcore-log: 
,08-11 12:30:46.526  4017  4063 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 12:30:46.526  4017  4063 I jxcore-log: 
,08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:30:46.538  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:30:46.543  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:30:46.546  4017  4063 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 12:30:46.546  4017  4063 I jxcore-log: 
,08-11 12:30:46.548  4017  4063 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 12:30:46.548  4017  4063 I jxcore-log: 
,08-11 12:30:46.881  4017  4063 I jxcore-log: Running unit tests
08-11 12:30:46.881  4017  4063 I jxcore-log: 
,08-11 12:30:46.881  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:30:46.881  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@da29a84 added. We now have 2 listener(s)
,08-11 12:30:46.883  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 12:30:46.883  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:30:46.883  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:30:46.883  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 12:30:46.884  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f68326d added. We now have 2 listener(s)
08-11 12:30:46.884  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:30:46.885  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:30:46.891  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:30:46.904  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:30:46.910  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:30:46.911  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:30:46.912  4017  4063 D ExecuteNativeTests: Running unit tests
,08-11 12:30:46.914  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:46.917  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:46.997  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 12:30:46.997  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 added. We now have 3 listener(s)
08-11 12:30:46.998  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 12:30:46.998  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 12:30:46.998  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:30:46.999  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:30:46.999  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 added. We now have 3 listener(s)
08-11 12:30:46.999  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:30:46.999  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:30:47.009  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:30:47.026  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:30:47.031  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:47.031  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 12:30:47.033  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 12:30:47.033  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:30:47.033  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:30:47.034  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 12:30:47.035  4017  4063 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-11 12:30:47.035  4017  4063 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-11 12:30:47.035  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 12:30:47.035  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:30:47.035  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:30:47.035  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:30:47.036  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:30:47.036  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:30:47.036  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:30:47.036  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:30:47.037  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:47.037  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:30:47.037  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 12:30:47.037  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 removed from the list
08-11 12:30:47.037  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:30:47.037  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 removed from the list
,08-11 12:30:47.038  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:30:47.040  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:30:47.040  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:30:47.041  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:47.042  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:47.042  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:47.044  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:30:47.044  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:30:47.044  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:30:47.044  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:30:47.046  4017  4063 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-11 12:30:47.046  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:30:47.046  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:30:47.046  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:30:47.046  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:30:47.047  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:47.047  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:47.047  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:30:47.047  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:30:47.047  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:30:47.047  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:30:47.047  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:30:47.047  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:47.047  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:47.047  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:30:47.048  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:30:47.048  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:30:47.048  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:30:47.048  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:30:47.052  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-11 12:30:47.052  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 12:30:47.052  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 12:30:47.052  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 12:30:47.052  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 12:30:47.053  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-11 12:30:47.054  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 12:30:47.054  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 12:30:47.054  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-11 12:30:47.054  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 12:30:47.054  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-11 12:30:47.054  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 12:30:47.054  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 12:30:47.054  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:30:47.054  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:30:47.054  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:30:47.054  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:30:47.054  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:47.054  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:47.054  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:30:47.054  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:30:47.055  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:30:47.055  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:30:47.055  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:47.055  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:47.055  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:47.055  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:47.057  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:30:47.057  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:30:47.057  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:30:47.057  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:30:47.058  4017  4063 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 12:30:47.059  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:30:47.063  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:30:47.065  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:47.065  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:30:47.065  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:30:47.066  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 12:30:47.066  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 12:30:47.066  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:30:47.066  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:30:47.067  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:30:47.069  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:47.071  4017  4063 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 12:30:47.071  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 12:30:47.077  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:30:47.079  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 12:30:47.080  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 12:30:47.082  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-11 12:30:47.085  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-11 12:30:47.085  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 12:30:47.086  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 12:30:47.086  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 12:30:47.087  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:30:47.090  2708  2881 D BtGatt.GattService: registerClient() - UUID=bbdc6c4b-3dae-47d7-9891-25143ee19ca8
,08-11 12:30:47.092  2708  2728 D BtGatt.GattService: onClientRegistered() - UUID=bbdc6c4b-3dae-47d7-9891-25143ee19ca8, clientIf=5
08-11 12:30:47.092  4017  4028 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 12:30:47.093  2708  2898 D BtGatt.GattService: start scan with filters
,08-11 12:30:47.096  2708  2732 D BtGatt.ScanManager: handling starting scan
,08-11 12:30:47.100  2708  2732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:30:47.100  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 12:30:47.100  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 12:30:47.100  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 12:30:47.101  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 12:30:47.103  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 12:30:47.103  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 12:30:47.104  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 12:30:47.105  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 12:30:47.107  2708  2728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 12:30:47.107  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:47.108  2708  2732 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-11 12:30:47.108  4017  4063 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 12:30:47.113  2708  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 12:30:47.113  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:47.113  2708  2732 D BtGatt.ScanManager: Starting BLE batch scan
08-11 12:30:47.113  2708  2732 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 12:30:47.124  2708  2728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 12:30:47.124  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:47.132  2708  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 12:30:47.132  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:47.607  4017  4017 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 12:30:47.607  4017  4017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:30:47.608  4017  4017 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 12:30:48.640  2708  2708 D BtGatt.ScanManager: awakened up at time 331860
08-11 12:30:48.642  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:30:48.711  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-11 12:30:48.712  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:48.713  2708  2728 D BtGatt.GattService: current time is 331933166399
,08-11 12:30:48.715  2708  2728 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -82, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -106, -15, -31, -128, 20, -7, 1, 0, -101, 29, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 26, 102, -43, 2, 2, -29, 21, 62, 11, -11, -61, 28, 6, 8, 116, 105, 115, 54, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 5, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -89, 16, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -92, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -87, 11, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 12:30:48.720  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 12:30:48.723  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 26, 102, -43, 2, 2, -29, 21, 62, 11, -11, -61, 6, 8, 116, 105, 115, 54, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
,08-11 12:30:48.724  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,08-11 12:30:48.725  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
08-11 12:30:48.725  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,08-11 12:30:48.727  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 12:30:48.728  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 12:30:50.215  2708  2708 D BtGatt.ScanManager: awakened up at time 333435
,08-11 12:30:50.218  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:30:50.229  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 12:30:50.229  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:51.732  2708  2708 D BtGatt.ScanManager: awakened up at time 334953
,08-11 12:30:51.735  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:30:51.747  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 12:30:51.747  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:52.118  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:30:52.118  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 12:30:52.119  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 12:30:52.119  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:30:52.119  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 12:30:52.120  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,08-11 12:30:52.121  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 12:30:52.121  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 12:30:52.121  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 12:30:52.124  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-11 12:30:52.124  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 12:30:52.126  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:30:52.129  2708  2898 D BtGatt.GattService: stopScan() - queue size =1
08-11 12:30:52.131  2708  2720 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 12:30:52.135  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-11 12:30:52.135  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 12:30:52.136  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-11 12:30:52.136  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,08-11 12:30:52.137  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 12:30:52.142  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 12:30:52.144  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-11 12:30:52.145  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,08-11 12:30:52.146  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 12:30:52.149  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 12:30:52.152  2708  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 12:30:52.152  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:30:52.152  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 12:30:52.152  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:52.152  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:30:52.152  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:30:52.152  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:52.152  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:30:52.152  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:30:52.152  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:30:52.152  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:30:52.152  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:30:52.152  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:52.152  2708  2732 D BtGatt.ScanManager: stopping BLe Batch
,08-11 12:30:52.161  2708  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 12:30:52.161  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:52.161  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:30:52.177  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
08-11 12:30:52.177  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:52.177  2708  2728 D BtGatt.GattService: current time is 335397718942
08-11 12:30:52.177  2708  2728 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -85, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -83, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -79, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 12:30:52.177  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 12:30:52.178  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 12:30:52.178  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 12:30:52.653  4017  4017 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 12:30:57.154  4017  4063 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-11 12:30:57.161  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:30:57.176  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:30:57.183  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:30:57.184  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 12:30:57.184  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:30:57.185  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 12:30:57.185  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 12:30:57.186  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:30:57.186  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 12:30:57.192  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:57.198  4017  4063 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 12:30:57.198  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 12:30:57.201  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:57.211  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:30:57.213  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-11 12:30:57.213  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 12:30:57.222  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 12:30:57.222  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 12:30:57.223  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 12:30:57.225  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:30:57.231  2708  2897 D BtGatt.GattService: registerClient() - UUID=e02164e1-3c14-4151-a154-b4682fb0a40a
,08-11 12:30:57.232  2708  2728 D BtGatt.GattService: onClientRegistered() - UUID=e02164e1-3c14-4151-a154-b4682fb0a40a, clientIf=5
,08-11 12:30:57.233  4017  4028 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 12:30:57.234  2708  2719 D BtGatt.GattService: start scan with filters
,08-11 12:30:57.242  2708  2732 D BtGatt.ScanManager: handling starting scan
,08-11 12:30:57.242  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 12:30:57.242  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-11 12:30:57.242  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 12:30:57.243  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 12:30:57.252  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 12:30:57.253  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 12:30:57.253  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 12:30:57.258  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 12:30:57.259  2708  2728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-11 12:30:57.259  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:57.260  2708  2732 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-11 12:30:57.261  4017  4063 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 12:30:57.264  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:30:57.265  4017  4063 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-11 12:30:57.265  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 12:30:57.265  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 12:30:57.265  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:30:57.265  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 12:30:57.265  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 12:30:57.265  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 12:30:57.265  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 12:30:57.265  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 12:30:57.266  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 12:30:57.266  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 12:30:57.266  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:30:57.267  2708  2898 D BtGatt.GattService: stopScan() - queue size =1
08-11 12:30:57.268  2708  2720 D BtGatt.GattService: unregisterClient() - clientIf=5
08-11 12:30:57.269  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:30:57.269  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 12:30:57.269  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 12:30:57.269  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 12:30:57.269  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 12:30:57.271  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:30:57.271  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 12:30:57.271  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 12:30:57.271  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 12:30:57.271  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 12:30:57.272  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:30:57.273  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:30:57.273  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:30:57.273  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:30:57.273  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:57.273  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:30:57.273  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:30:57.273  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:30:57.273  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:30:57.273  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:30:57.273  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:57.274  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:30:57.274  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:30:57.275  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:30:57.275  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:30:57.275  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:30:57.275  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:30:57.276  4017  4063 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-11 12:30:57.278  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:30:57.279  2708  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 12:30:57.280  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:57.280  2708  2732 D BtGatt.ScanManager: Starting BLE batch scan
08-11 12:30:57.280  2708  2732 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:30:57.285  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:30:57.287  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:30:57.288  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 12:30:57.289  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:30:57.289  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-11 12:30:57.290  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-11 12:30:57.290  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:30:57.290  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:30:57.291  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:57.295  4017  4063 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 12:30:57.295  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 12:30:57.296  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:30:57.299  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:30:57.300  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 12:30:57.300  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 12:30:57.303  2708  2728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 12:30:57.303  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:57.305  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 12:30:57.305  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 12:30:57.305  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-11 12:30:57.306  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:30:57.309  2708  2898 D BtGatt.GattService: registerClient() - UUID=052384b1-59ca-49cf-a66c-8787d86c7ff3
,08-11 12:30:57.309  2708  2728 D BtGatt.GattService: onClientRegistered() - UUID=052384b1-59ca-49cf-a66c-8787d86c7ff3, clientIf=5
08-11 12:30:57.310  4017  4028 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-11 12:30:57.310  2708  2720 D BtGatt.GattService: start scan with filters
,08-11 12:30:57.313  2708  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 12:30:57.313  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:57.313  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-11 12:30:57.313  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 12:30:57.313  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,08-11 12:30:57.313  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-11 12:30:57.316  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-11 12:30:57.317  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 12:30:57.317  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 12:30:57.319  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 12:30:57.321  4017  4063 I io.jxcore.node.ConnectionHelper: start: OK
,08-11 12:30:57.327  2708  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 12:30:57.327  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:57.327  2708  2732 D BtGatt.ScanManager: stopping BLe Batch
,08-11 12:30:57.337  2708  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 12:30:57.337  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:57.337  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:30:57.346  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 12:30:57.346  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:57.348  2708  2732 D BtGatt.ScanManager: handling starting scan
,08-11 12:30:57.358  2708  2728 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 12:30:57.358  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:57.359  2708  2732 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 12:30:57.372  2708  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,08-11 12:30:57.372  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:57.373  2708  2732 D BtGatt.ScanManager: Starting BLE batch scan
08-11 12:30:57.373  2708  2732 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-11 12:30:57.406  2708  2728 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-11 12:30:57.406  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:57.424  2708  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,08-11 12:30:57.425  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:30:57.818  4017  4017 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,08-11 12:30:57.818  4017  4017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
08-11 12:30:57.819  4017  4017 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 12:30:58.928  2708  2708 D BtGatt.ScanManager: awakened up at time 342148
,08-11 12:30:58.936  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:30:58.991  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:30:58.996  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,08-11 12:30:58.996  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:30:58.997  2708  2728 D BtGatt.GattService: current time is 342217342006
,08-11 12:30:58.997  2708  2728 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -83, 8, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 35, 97, 126, -92, 22, -56, 1, -128, -80, 6, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -91, 4, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -93, 3, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 71, -122, -77, 84, 69, -12, 1, -128, -88, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -82, 18, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 37, -47, 14, -113, 116, -46, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 12:30:58.997  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
08-11 12:30:58.998  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
,08-11 12:30:58.998  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
08-11 12:30:58.998  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,08-11 12:30:58.998  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
08-11 12:30:58.999  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
08-11 12:30:58.999  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,08-11 12:30:59.010  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:30:59.015  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:30:59.042  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-11 12:30:59.043  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-11 12:30:59.043  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:30:59.043  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:30:59.055  1492  2049 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-11 12:30:59.055  1492  2049 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-11 12:30:59.055  1492  2049 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-11 12:30:59.055  1492  2049 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-11 12:30:59.055  1492  2049 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-11 12:30:59.055  1492  2049 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-11 12:30:59.055  1492  2049 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 12:30:59.059  3536  3569 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-11 12:30:59.059  3536  3569 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-11 12:30:59.059  3536  3569 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-11 12:30:59.059  3536  3569 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-11 12:30:59.059  3536  3569 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-11 12:30:59.059  3536  3569 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-11 12:30:59.059  3536  3569 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,08-11 12:31:00.505  2708  2708 D BtGatt.ScanManager: awakened up at time 343725
,08-11 12:31:00.508  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:31:00.517  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-11 12:31:00.517  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:02.019  2708  2708 D BtGatt.ScanManager: awakened up at time 345239
,08-11 12:31:02.021  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:31:02.033  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-11 12:31:02.033  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:02.322  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:31:02.322  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:02.322  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 12:31:02.323  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:02.323  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-11 12:31:02.323  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 12:31:02.324  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 12:31:02.324  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 12:31:02.324  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 12:31:02.325  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 12:31:02.326  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-11 12:31:02.328  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:31:02.330  2708  2719 D BtGatt.GattService: stopScan() - queue size =1
,08-11 12:31:02.332  2708  2881 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 12:31:02.333  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:31:02.334  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-11 12:31:02.334  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-11 12:31:02.334  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 12:31:02.335  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-11 12:31:02.339  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 12:31:02.339  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 12:31:02.340  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 12:31:02.340  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 12:31:02.343  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 12:31:02.346  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 12:31:02.346  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,08-11 12:31:02.347  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:31:02.348  2708  2728 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
08-11 12:31:02.348  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:02.348  2708  2732 D BtGatt.ScanManager: stopping BLe Batch
,08-11 12:31:02.358  2708  2728 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,08-11 12:31:02.358  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:31:02.359  2708  2732 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:31:02.375  2708  2728 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 12:31:02.375  2708  2728 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:02.376  2708  2728 D BtGatt.GattService: current time is 345596493077
08-11 12:31:02.376  2708  2728 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -78, 7, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 12:31:02.377  2708  2728 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 12:31:02.848  4017  4017 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 12:31:02.849  4017  4017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:02.849  4017  4017 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 12:31:07.347  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:31:07.348  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:07.348  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:31:07.349  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:31:07.349  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.349  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:31:07.350  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
,08-11 12:31:07.350  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.350  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.351  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:07.351  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.353  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:07.353  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.357  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:07.357  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.357  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.358  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.360  4017  4063 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-11 12:31:07.362  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.362  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:07.362  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:07.363  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.363  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.363  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.364  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.364  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.364  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:07.365  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:07.365  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.365  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.366  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.366  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.368  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:07.369  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.369  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.369  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:07.370  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-11 12:31:07.370  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.370  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:07.370  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:31:07.370  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.370  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.370  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.370  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.371  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.371  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.371  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:07.371  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.371  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.371  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.371  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.373  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:07.373  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.373  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.373  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:07.374  4017  4063 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-11 12:31:07.374  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.374  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:07.374  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:07.374  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.374  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.375  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.375  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.375  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.375  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.375  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:07.375  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.375  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.375  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.375  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.376  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:31:07.376  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.376  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.376  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.377  4017  4063 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-11 12:31:07.377  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.377  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:07.377  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:31:07.378  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.378  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.378  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.378  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.378  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.378  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.378  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:07.378  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.378  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.378  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.378  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.381  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:07.381  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.381  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:07.381  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.381  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-11 12:31:07.382  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:31:07.382  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-11 12:31:07.382  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 12:31:07.382  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:31:07.382  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:31:07.382  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-11 12:31:07.382  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:31:07.382  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-11 12:31:07.383  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.383  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:31:07.383  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:07.383  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.383  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.383  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.383  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.383  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.383  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.384  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:07.384  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.384  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.384  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.384  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.385  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:31:07.386  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.386  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.386  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.387  4017  4063 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 12:31:07.387  4017  4063 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 12:31:07.387  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-11 12:31:07.393  4017  4063 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-11 12:31:07.393  4017  4063 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,08-11 12:31:07.393  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-11 12:31:07.393  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-11 12:31:07.393  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-11 12:31:07.394  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-11 12:31:07.394  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-11 12:31:07.394  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,08-11 12:31:07.394  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-11 12:31:07.394  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-11 12:31:07.394  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310],
,08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-11 12:31:07.395  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-11 12:31:07.396  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-11 12:31:07.396  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-11 12:31:07.396  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
,08-11 12:31:07.396  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-11 12:31:07.396  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-11 12:31:07.396  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-11 12:31:07.396  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-11 12:31:07.397  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-11 12:31:07.397  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-11 12:31:07.397  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-11 12:31:07.400  4017  4063 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,08-11 12:31:07.401  4017  4063 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 12:31:07.401  4017  4063 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-11 12:31:07.401  4017  4063 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-11 12:31:07.401  4017  4063 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 12:31:07.402  4017  4063 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-11 12:31:07.402  4017  4063 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-11 12:31:07.402  4017  4063 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-11 12:31:07.402  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-11 12:31:07.405  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,08-11 12:31:07.406  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-11 12:31:07.407  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-11 12:31:07.408  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-11 12:31:07.408  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-11 12:31:07.408  4017  4063 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-11 12:31:07.409  4017  4063 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-11 12:31:07.409  4017  4063 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-11 12:31:07.410  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.410  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:31:07.410  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:07.410  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.410  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:07.410  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.411  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-11 12:31:07.412  4017  4070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 429)
,08-11 12:31:07.412  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.413  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.413  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:07.413  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:07.413  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:07.413  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.413  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.413  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.415  4017  4070 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:31:07.417  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:07.417  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 12:31:07.417  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.417  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.418  4017  4063 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-11 12:31:07.418  4017  4071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 429
,08-11 12:31:07.418  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.418  4017  4071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 429)
08-11 12:31:07.418  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything,
08-11 12:31:07.419  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:07.419  4017  4071 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 429)
08-11 12:31:07.419  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.419  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:07.419  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.419  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
,08-11 12:31:07.419  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.419  4017  4070 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 429)
08-11 12:31:07.419  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.419  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:07.419  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.419  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.419  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:07.420  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.421  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:07.421  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-11 12:31:07.421  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.421  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.422  4017  4063 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-11 12:31:07.422  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:31:07.422  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:07.422  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:07.423  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:31:07.423  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.423  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.423  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.423  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:07.423  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.423  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:07.423  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.423  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.423  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.423  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.424  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:31:07.424  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.424  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.425  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.425  4017  4063 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,08-11 12:31:07.425  4017  4063 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-11 12:31:07.425  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 12:31:07.425  4017  4063 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,08-11 12:31:07.426  4017  4063 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 12:31:07.426  4017  4063 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-11 12:31:07.426  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 12:31:07.426  4017  4063 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
,08-11 12:31:07.426  4017  4063 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-11 12:31:07.426  4017  4063 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-11 12:31:07.426  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 12:31:07.426  4017  4063 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,08-11 12:31:07.426  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:07.427  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:07.427  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:07.427  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-11 12:31:07.427  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.427  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.427  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
,08-11 12:31:07.427  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.427  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.427  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:07.427  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:07.427  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:07.427  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.428  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.428  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:07.428  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:07.428  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.429  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:07.429  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:07.429  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.429  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.429  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:07.429  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:07.429  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:07.430  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:07.430  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:07.430  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:07.460  2708  2867 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 4, channel: -1
,08-11 12:31:12.430  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:12.431  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.431  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:31:12.432  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.432  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:12.432  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:12.433  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:12.433  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:31:12.433  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-11 12:31:12.434  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:31:12.435  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.435  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:12.435  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:12.436  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:12.436  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.436  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:12.436  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.437  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:12.437  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.437  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:12.442  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:31:12.442  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:12.442  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:12.443  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:12.449  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 12:31:12.450  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:31:12.452  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-11 12:31:12.454  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 12:31:12.454  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-11 12:31:12.455  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 12:31:12.455  4017  4017 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-11 12:31:12.455  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 12:31:12.455  4017  4072 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:31:12.456  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:12.456  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-11 12:31:12.457  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,08-11 12:31:12.457  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-11 12:31:12.457  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:12.457  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,08-11 12:31:12.457  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
,08-11 12:31:12.458  4017  4017 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-11 12:31:12.458  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:12.458  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 12:31:12.458  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,08-11 12:31:12.458  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,08-11 12:31:12.458  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.458  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:12.459  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:31:12.459  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:31:12.459  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:12.460  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:31:12.460  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:12.460  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 12:31:12.460  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:12.460  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:12.460  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:12.460  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.460  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.460  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:12.460  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.460  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:12.460  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:12.461  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.461  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.461  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.461  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:12.462  4017  4072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-11 12:31:12.462  4017  4072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-11 12:31:12.462  4017  4072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 12:31:12.463  4017  4017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 12:31:12.464  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:31:12.464  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:12.464  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.465  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.470  4017  4063 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-11 12:31:12.470  4017  4063 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
,08-11 12:31:12.471  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-11 12:31:12.471  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:31:12.471  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-11 12:31:12.471  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:12.471  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:31:12.471  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:12.472  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:12.472  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.472  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.472  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
,08-11 12:31:12.472  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.472  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.472  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:12.472  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.472  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.472  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.472  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.474  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:12.474  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:12.474  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.475  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
,08-11 12:31:12.479  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-11 12:31:12.480  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:12.480  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:12.480  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:12.480  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:12.480  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.480  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:12.480  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.481  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.481  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:12.481  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.481  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.481  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.481  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.482  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:31:12.482  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:12.482  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.482  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.483  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
08-11 12:31:12.483  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:12.483  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:12.484  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:12.484  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.484  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.484  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2757323 not in the list
08-11 12:31:12.484  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.484  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.484  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:12.484  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.484  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.484  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.485  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.486  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:12.486  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:12.486  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.486  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@528e020 not in the list
08-11 12:31:12.487  4017  4063 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-11 12:31:12.487  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 12:31:12.487  4017  4063 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-11 12:31:12.487  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-11 12:31:12.488  4017  4063 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-11 12:31:12.488  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-11 12:31:12.490  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-11 12:31:12.490  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-11 12:31:12.492  4017  4063 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-11 12:31:12.492  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 12:31:12.492  4017  4063 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-11 12:31:12.492  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-11 12:31:12.492  4017  4063 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-11 12:31:12.492  4017  4063 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-11 12:31:12.493  4017  4063 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-11 12:31:12.493  4017  4063 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-11 12:31:12.493  4017  4063 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-11 12:31:12.493  4017  4063 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-11 12:31:12.493  4017  4063 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-11 12:31:12.493  4017  4063 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-11 12:31:12.494  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:31:12.494  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d245602 added. We now have 3 listener(s)
08-11 12:31:12.495  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:31:12.496  4017  4063 D BluetoothAdapter: enable(): BT is already enabled..!
08-11 12:31:12.496   873  1703 D WifiService: setWifiEnabled: true pid=4017, uid=10000
08-11 12:31:12.496   873  1703 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 12:31:12.497  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:31:12.497  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2396b13 added. We now have 4 listener(s)
08-11 12:31:12.498  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:31:12.502  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.502  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2396b13 removed from the list
08-11 12:31:12.502  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:12.502  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.502  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.503  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:31:12.503  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c49150 added. We now have 4 listener(s)
08-11 12:31:12.503  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:31:12.504  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:12.504  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c49150 removed from the list
08-11 12:31:12.504  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:12.504  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:12.504  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:12.505  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:31:12.505  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd86f49 added. We now have 4 listener(s)
08-11 12:31:12.505  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:31:12.507   873   884 D WifiService: setWifiEnabled: false pid=4017, uid=10000
08-11 12:31:12.507   873   884 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-11 12:31:12.513  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:31:12.514  2708  2724 D BluetoothAdapterState: Current state: ON, message: 23
08-11 12:31:12.514  2708  2724 D BluetoothAdapterProperties: Setting state to 13
08-11 12:31:12.514  2708  2724 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-11 12:31:12.515  2708  2724 D BluetoothAdapterProperties: onBluetoothDisable()
08-11 12:31:12.516  2708  2724 I BluetoothAdapterState: Entering PendingCommandState
08-11 12:31:12.519  2708  2708 D BluetoothMapService: onReceive
,08-11 12:31:12.520  2708  2708 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:31:12.520  2708  2708 D BluetoothMapService: STATE_TURNING_OFF
08-11 12:31:12.520  2708  2708 D BluetoothMapService: MAP Service closeService in
08-11 12:31:12.520  2708  2708 D BluetoothMapMasInstance0: MAP Service shutdown
08-11 12:31:12.520  2708  2708 D ObexServerSockets0: shutdown(block = true)
08-11 12:31:12.521  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 12:31:12.521  2708  2708 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 12:31:12.521  2708  2900 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-11 12:31:12.522  2708  2901 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-11 12:31:12.522  2708  2867 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-11 12:31:12.522  2708  2708 I BtOppRfcommListener: stopping Accept Thread
08-11 12:31:12.522  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:12.522  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:31:12.522  2708  3459 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:31:12.522  2708  3459 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-11 12:31:12.525  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.525  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:12.525  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:31:12.527  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-11 12:31:12.529   873  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-11 12:31:12.529   873  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-11 12:31:12.529   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 12:31:12.529   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-11 12:31:12.532  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.535  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.537   873   886 I ActivityManager: Start proc 4075:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-11 12:31:12.539  2708  2728 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:31:12.539  2708  2724 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-11 12:31:12.539  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:12.539  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:31:12.543   873  1304 E native  : do suspend true
08-11 12:31:12.544  2708  2708 D HeadsetService: Received stop request...Stopping profile...
08-11 12:31:12.543  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.546  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:12.546  2708  2827 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
08-11 12:31:12.547  2708  2827 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 4
08-11 12:31:12.547   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:12.547   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:12.549  1354  1374 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:12.549  1708  1729 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:12.549   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:12.551  2708  2708 D A2dpService: Received stop request...Stopping profile...
08-11 12:31:12.551  2708  2887 D A2dpStateMachine: Exit Disconnected: -1
08-11 12:31:12.552   873   873 D BluetoothA2dp: Proxy object disconnected
08-11 12:31:12.552  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:12.553  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:31:12.553  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:12.553  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:12.553  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:12.553  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:12.554  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.554  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:12.554   873  2140 D DhcpClient: Clearing IP address
08-11 12:31:12.556  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.554   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:31:12.557  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 12:31:12.557  2708  2708 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:31:12.557  2708  2728 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-11 12:31:12.557  2708  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:12.557  2708  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:12.557  2708  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:12.558  2708  2728 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-11 12:31:12.558  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.561  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-11 12:31:12.562  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-11 12:31:12.562  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.563  2708  2708 D HidService: Received stop request...Stopping profile...
08-11 12:31:12.563  2708  2708 D HidService: Stopping Bluetooth HidService
,08-11 12:31:12.565  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.567  2708  2708 D HealthService: Received stop request...Stopping profile...
08-11 12:31:12.567  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-11 12:31:12.567  1354  1354 D HidProfile: Bluetooth service disconnected
08-11 12:31:12.568  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:12.568  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:12.568  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:12.568  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:12.568  1492  2299 V NativeCrypto: Read error: ssl=0xaa216200: I/O error during system call, Connection timed out
08-11 12:31:12.569  2708  2728 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-11 12:31:12.569  2708  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:12.570  2708  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:12.570  2708  2708 D PanService: Received stop request...Stopping profile...
08-11 12:31:12.570  2708  2827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:31:12.570  2708  2827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:31:12.570  2708  2827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:31:12.571  2708  2827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:31:12.571  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 12:31:12.571  1354  1354 D PanProfile: Bluetooth service disconnected
08-11 12:31:12.572  1492  2299 V NativeCrypto: SSL shutdown failed: ssl=0xaa216200: I/O error during system call, Broken pipe
08-11 12:31:12.572  2708  2708 D BluetoothMapService: Received stop request...Stopping profile...
08-11 12:31:12.573  2708  2708 D BluetoothMapService: stop()
08-11 12:31:12.574  2708  2708 D BluetoothMapAppObserver: deinitObservers()
08-11 12:31:12.574  2708  2708 D BluetoothMapAppObserver: removeReceiver()
08-11 12:31:12.575  1354  1354 D BluetoothMap: Proxy object disconnected
08-11 12:31:12.575  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:12.575  1354  1354 D MapProfile: Bluetooth service disconnected
08-11 12:31:12.575  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:12.575  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:12.575  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:12.576  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...,
08-11 12:31:12.576  2708  2708 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-11 12:31:12.576   873  1715 D ConnectivityService: reportNetworkConnectivity(100, false) by 10011
08-11 12:31:12.576  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:12.576  2708  2708 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:12.576  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:12.576  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:12.577  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 12:31:12.577   873  2138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10011
08-11 12:31:12.577  2708  2728 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-11 12:31:12.577  2708  2728 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-11 12:31:12.577  2708  2708 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 12:31:12.580   873  2138 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-11 12:31:12.580   371   871 D CommandListener: Setting iface cfg
08-11 12:31:12.581   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-11 12:31:12.581   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-11 12:31:12.582   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-11 12:31:12.582   873  1304 D WifiStateMachine: Start Disconnecting Watchdog 1
,08-11 12:31:12.583   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-11 12:31:12.583   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-11 12:31:12.583   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-11 12:31:12.584   873  1304 E native  : do suspend true
08-11 12:31:12.588   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,08-11 12:31:12.589  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:12.589  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,08-11 12:31:12.589  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:12.589  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false,
08-11 12:31:12.590   398   398 E Parcel  : Reading a NULL string not supported here.
,08-11 12:31:12.590  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 12:31:12.591  2708  2708 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-11 12:31:12.592  2708  2708 D BluetoothMapService: MAP Service closeService in
,08-11 12:31:12.593  2708  2708 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:12.593  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,08-11 12:31:12.593  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:12.593  2708  2708 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:12.594  2708  2724 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-11 12:31:12.594  2708  2724 D BluetoothAdapterProperties: Setting state to 15
,08-11 12:31:12.594  2708  2724 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-11 12:31:12.595  2708  2724 I BluetoothAdapterState: Entering BleOnState
08-11 12:31:12.595  1354  1374 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-11 12:31:12.595  2708  2708 D BluetoothMapService: cleanup()
08-11 12:31:12.595  2708  2708 D BluetoothMapService: MAP Service closeService in
,08-11 12:31:12.595  1354  1370 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 12:31:12.596   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:31:12.596  1354  1826 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 12:31:12.597  1708  1729 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:31:12.597  1354  1374 D BluetoothMap: onBluetoothStateChange: up=false
,08-11 12:31:12.597  1354  1370 D BluetoothPan: onBluetoothStateChange on: false
,08-11 12:31:12.598   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 12:31:12.598  1354  1826 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 12:31:12.598   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 12:31:12.598   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:31:12.599  2708  2724 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-11 12:31:12.599  2708  2724 D BluetoothAdapterProperties: Setting state to 16
,08-11 12:31:12.599  2708  2724 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-11 12:31:12.599  2708  2724 D BluetoothAdapterProperties: onBleDisable
,08-11 12:31:12.600  2708  2724 I BluetoothAdapterState: Entering PendingCommandState
08-11 12:31:12.601  2708  2725 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-11 12:31:12.603   873  2141 D DhcpClient: Receive thread stopped
,08-11 12:31:12.604  2708  2827 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-11 12:31:12.604  2708  2827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:12.604  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:12.604  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:12.604  2708  2728 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:31:12.604  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.604  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:12.607  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:12.607  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:12.607  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.607  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:12.609  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:12.610  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:12.610  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:12.610  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:12.612  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:12.613  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.614  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.619  4075  4075 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,08-11 12:31:12.630   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 12:31:12.632  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 12:31:12.637  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 12:31:12.641   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8c1b68:true
,08-11 12:31:12.650   873   883 I ActivityManager: Start proc 4094:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-11 12:31:12.652   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-11 12:31:12.652   371   871 D CommandListener: Clearing all IP addresses on wlan0
08-11 12:31:12.653   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true,
08-11 12:31:12.653   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-11 12:31:12.654   873  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 12:31:12.655   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-11 12:31:12.658  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:12.659  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:12.661  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:12.671  4075  4075 D LocalBluetoothProfileManager: Adding local MAP profile
,08-11 12:31:12.672   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 12:31:12.674   873  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-11 12:31:12.674  1821  2057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:31:12.675  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:12.675  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:12.675  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.676  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:12.677  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:12.677  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:12.677  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:12.678  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:12.679  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:12.679  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:12.680  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:12.680  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:12.687  4075  4075 D BluetoothMap: Create BluetoothMap proxy object
,08-11 12:31:12.696  4075  4075 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-11 12:31:12.701  4094  4094 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,08-11 12:31:12.707   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-11 12:31:12.708   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 12:31:12.710  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,08-11 12:31:12.718   873  1732 I ActivityManager: Killing 2607:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-11 12:31:12.806  2708  2728 I bt_hci  : shut_down
08-11 12:31:12.807  2708  2733 D bt_hwcfg: hw_epilog_process
,08-11 12:31:12.819  2708  2733 I bt_vendor: low_power_mode_cb
,08-11 12:31:12.842  2708  2733 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
08-11 12:31:12.842  2708  2733 I bt_vendor: epilog_cb
08-11 12:31:12.842  2708  2733 I bt_hci  : epilog_finished_callback
,08-11 12:31:12.848  2708  2728 I bt_hci_h4: hal_close
,08-11 12:31:12.849  2708  2728 I bt_userial_vendor: device fd = 51 close
,08-11 12:31:12.890  4094  4094 D StrictMode: StrictMode policy violation; ~duration=116 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 12:31:12.890  4094  4094 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 12:31:12.890  4094  4094 D StrictMode: StrictMode policy violation; ~duration=115 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 12:31:12.890  4094  4094 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 12:31:12.890  4094  4094 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.k.d(PG:583)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:170)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:31:12.890  4094  4094 D StrictMode: StrictMode policy violation; ~duration=94 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.890  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:31:12.891  4094  4094 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at java.io.File.exists(File.java:361)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.891  4094  4094 D StrictMode: ,	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:31:12.891  4094  4094 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:31:12.891  4094  4094 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-11 12:31:12.937   873  1730 I ActivityManager: Start proc 4128:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
,08-11 12:31:12.940   873  1730 I ActivityManager: Killing 3518:android.process.acore/u0a5 (adj 15): empty #17
,08-11 12:31:12.961  4017  4017 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 12:31:13.012  2708  2725 D bt_stack_manager: event_shut_down_stack finished.
,08-11 12:31:13.012  2708  2724 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 12:31:13.018  2708  2708 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 12:31:13.018  2708  2724 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,08-11 12:31:13.019  2708  2708 D BtGatt.GattService: Received stop request...Stopping profile...
,08-11 12:31:13.019  2708  2708 D BtGatt.GattService: stop()
08-11 12:31:13.020  2708  2708 D BtGatt.AdvertiseManager: advertise clients cleared,
,08-11 12:31:13.023  2708  2708 V BluetoothAdapterState: isTurningOff()=false
,08-11 12:31:13.023  2708  2708 V BluetoothAdapterState: isTurningOn()=false
,08-11 12:31:13.023  2708  2708 V BluetoothAdapterState: isBleTurningOn()=false,
,08-11 12:31:13.024  2708  2708 V BluetoothAdapterState: isBleTurningOff()=true
,08-11 12:31:13.024  2708  2724 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-11 12:31:13.025  2708  2724 D BluetoothAdapterProperties: Setting state to 10
,08-11 12:31:13.025  2708  2724 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-11 12:31:13.026  2708  2724 I BluetoothAdapterState: Entering OffState
08-11 12:31:13.028   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,08-11 12:31:13.029  4128  4128 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,08-11 12:31:13.041  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-11 12:31:13.041  2708  2708 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,08-11 12:31:13.041  2708  2725 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-11 12:31:13.043  2708  2725 D bt_stack_manager: event_clean_up_stack finished.
,08-11 12:31:13.043  2708  2708 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-11 12:31:13.047  2708  2708 I art     : System.exit called, status: 0
,08-11 12:31:13.047  2708  2708 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 12:31:13.140   873  1771 I ActivityManager: Process com.android.bluetooth (pid 2708) has died
,08-11 12:31:13.320  4128  4148 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,08-11 12:31:13.320  4128  4148 I Babel_SMS: MmsConfig.loadMmsSettings
,08-11 12:31:13.321  4128  4148 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-11 12:31:13.321  4128  4148 I Babel_SMS: MmsConfig.loadFromDatabase
,08-11 12:31:13.400  4128  4148 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,08-11 12:31:13.401  4128  4148 I Babel_SMS: MmsConfig.loadFromResources
,08-11 12:31:13.402  4128  4148 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,08-11 12:31:13.402  4128  4148 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,08-11 12:31:13.418  4128  4128 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 12:31:13.421  4128  4128 I Babel_Crash: startup - clean
,08-11 12:31:13.444  4128  4128 I Babel_telephony: TeleModule.launchCompleted
,08-11 12:31:13.449  4094  4117 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-11 12:31:13.455   873  1386 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-11 12:31:13.467  4128  4128 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,08-11 12:31:13.475  4128  4128 W Babel   : BAM#gBA: invalid account id: -1
,08-11 12:31:13.475  4128  4128 W Babel   : BAM#gBA: invalid account id: -1
,08-11 12:31:13.475  4128  4128 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,08-11 12:31:13.479  4128  4153 I Babel   : deleted: false for 0
,08-11 12:31:13.494   873  1715 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,08-11 12:31:13.506  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 12:31:13.537   873  1771 I ActivityManager: Start proc 4156:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver
,08-11 12:31:13.540  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,08-11 12:31:13.577  4128  4128 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 12:31:13.655  4128  4128 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-11 12:31:13.674  4128  4128 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-11 12:31:13.675  4128  4128 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 12:31:13.681   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ee3f899:true
,08-11 12:31:13.686  4128  4128 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 12:31:13.710  4128  4128 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-11 12:31:13.720  4156  4156 D AdapterServiceConfig: Adding HeadsetService
,08-11 12:31:13.720  4156  4156 D AdapterServiceConfig: Adding A2dpService
,08-11 12:31:13.720  4156  4156 D AdapterServiceConfig: Adding HidService
,08-11 12:31:13.720  4156  4156 D AdapterServiceConfig: Adding HealthService
,08-11 12:31:13.720  4156  4156 D AdapterServiceConfig: Adding PanService
,08-11 12:31:13.720  4156  4156 D AdapterServiceConfig: Adding GattService
,08-11 12:31:13.720  4156  4156 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 12:31:13.722   873  1733 I ActivityManager: Killing 3799:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,08-11 12:31:13.771  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 12:31:13.773  4128  4128 I vclib   : onServiceConnected
,08-11 12:31:13.803  1852  1852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 12:31:13.807  1852  1852 D SystemUpdateService: onCreate
,08-11 12:31:13.816  1852  1852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 12:31:13.823  1852  4168 I SystemUpdateService: active receiver: enabled
,08-11 12:31:13.825  1852  4168 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 12:31:13.830  1852  4168 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-11 12:31:13.830  1852  4168 I SystemUpdateService: now status is 0 (complete)
08-11 12:31:13.830  1852  4168 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-11 12:31:13.831  1852  4168 I SystemUpdateService: file has been verified
08-11 12:31:13.831  1852  4168 I SystemUpdateService: OTA package size = 12249756
,08-11 12:31:13.839  1852  4168 I SystemUpdateService: showing system update notification
,08-11 12:31:13.848  1852  1852 D SystemUpdateService: onDestroy
,08-11 12:31:13.856  1852  1852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-11 12:31:13.861  1852  1852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 12:31:13.861  1852  2387 I iu.UploadsManager: num queued entries: 0
08-11 12:31:13.863  1852  1852 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 12:31:13.863  1852  2387 I iu.UploadsManager: num updated entries: 0
,08-11 12:31:13.869  1852  2387 I iu.SyncManager: NEXT; no task
,08-11 12:31:13.878   873  1703 I ActivityManager: Start proc 4170:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,08-11 12:31:13.913  4170  4170 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,08-11 12:31:13.916  4170  4170 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:31:13.923  4170  4170 D SprintDMHelper: simOperator: 
,08-11 12:31:13.923  4170  4170 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 12:31:13.958   873  1703 I ActivityManager: Start proc 4182:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-11 12:31:13.959   873  1703 I ActivityManager: Killing 3815:com.android.musicfx/u0a18 (adj 15): empty #17
,08-11 12:31:14.132   873  1386 I ActivityManager: Start proc 4197:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,08-11 12:31:14.136  4128  4196 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,08-11 12:31:14.142   873  1379 I ActivityManager: Killing 3421:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,08-11 12:31:14.224  4197  4197 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,08-11 12:31:14.285  4197  4197 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
08-11 12:31:14.285  4197  4197 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-11 12:31:14.285  4197  4197 I GAv4    :   adb logcat -s GAv4
,08-11 12:31:14.301  4197  4197 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,08-11 12:31:14.308  4197  4197 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,08-11 12:31:14.338  4197  4214 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,08-11 12:31:14.446  4197  4197 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,08-11 12:31:14.488  4197  4197 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,08-11 12:31:14.500  4197  4197 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 7714-7720)
08-11 12:31:14.501  4197  4197 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 12:31:14.511  4197  4197 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8089724}
08-11 12:31:14.511  4197  4197 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:31:14.512  4197  4197 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 12:31:14.521  4197  4197 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 12:31:14.522  4197  4197 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-11 12:31:14.548  4197  4197 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 12:31:14.562  4197  4197 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:31:14.562  4197  4197 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:31:14.563  4197  4197 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-11 12:31:14.563  4197  4197 I Adreno  : Build Date                       : 10/20/15
08-11 12:31:14.563  4197  4197 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-11 12:31:14.563  4197  4197 I Adreno  : Local Branch                     : M14
08-11 12:31:14.563  4197  4197 I Adreno  : Remote Branch                    : 
08-11 12:31:14.563  4197  4197 I Adreno  : Remote Branch                    : 
08-11 12:31:14.563  4197  4197 I Adreno  : Reconstruct Branch               : 
,08-11 12:31:14.630  4197  4197 I NSApplication: Starting up...
,08-11 12:31:14.641  4197  4243 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-11 12:31:14.666   873  1731 I ActivityManager: Start proc 4248:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-11 12:31:14.668   873  1731 I ActivityManager: Killing 3757:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-11 12:31:14.742  4248  4248 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-11 12:31:14.921   873   883 I ActivityManager: Killing 3837:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,08-11 12:31:17.527   873   883 D WifiService: setWifiEnabled: true pid=4017, uid=10000
,08-11 12:31:17.527   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:31:17.535   873  1304 D WifiConfigStore: Loading config and enabling all networks ,
,08-11 12:31:17.538  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:17.538  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:17.538  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:17.538  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:17.540  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:17.540  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:17.540  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:17.540  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:17.541  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:17.541  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:17.541  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:17.541  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:17.557   873  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-11 12:31:17.558   873  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,08-11 12:31:17.558   873  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-11 12:31:17.559   873  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-11 12:31:17.559   873  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,08-11 12:31:17.559   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,08-11 12:31:17.559   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 12:31:17.567   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-11 12:31:17.567   873  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
08-11 12:31:17.568   371   871 D CommandListener: Setting iface cfg
,08-11 12:31:17.569   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)',
08-11 12:31:17.569   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-11 12:31:17.578   873  1304 E native  : do suspend true
,08-11 12:31:17.578   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 12:31:17.584   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 12:31:17.601   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 12:31:18.428   873  1771 I ActivityManager: Killing 1798:com.google.android.googlequicksearchbox:search/u0a28 (adj 15): empty #17
,08-11 12:31:18.483   873  1305 D WifiService: Client connection lost with reason: 4
,08-11 12:31:18.963   873  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 12:31:19.003   873  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.31 rxSuccessRate=6.69 delta 1000 -> 994
08-11 12:31:19.004   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
08-11 12:31:19.004   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 12:31:19.021   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-11 12:31:19.092   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-11 12:31:19.098  1452  1452 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-11 12:31:19.521  1452  1452 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 12:31:19.565  1452  1452 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-11 12:31:19.566  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 12:31:19.569   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 12:31:19.582   873  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 12:31:19.582   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-11 12:31:19.582   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 12:31:19.601   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 12:31:19.612   371   871 D CommandListener: Setting iface cfg
,08-11 12:31:19.613   873  1304 D WifiStateMachine: Start Dhcp Watchdog 2
,08-11 12:31:19.619   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 12:31:19.672   873  4276 D DhcpClient: Receive thread started
,08-11 12:31:19.760   873  1304 E native  : do suspend false
,08-11 12:31:19.776   873  2140 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 12:31:19.787   873  4276 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172460, domain null
,08-11 12:31:19.789   873  2140 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172460 seconds
,08-11 12:31:19.792   873  2140 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 12:31:19.803   873  4276 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 12:31:19.804   873  2140 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-11 12:31:19.809   371   871 D CommandListener: Setting iface cfg
,08-11 12:31:19.812   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 12:31:19.816   873  1304 E native  : do suspend true
,08-11 12:31:19.817   873  2140 D DhcpClient: Scheduling renewal in 86399s
,08-11 12:31:19.829   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,08-11 12:31:19.830   873  1304 D WifiConfigStore: No blacklist allowed without epno enabled
,08-11 12:31:19.830   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-11 12:31:19.831   873  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-11 12:31:19.833   873  1306 D ConnectivityService: Adding iface wlan0 to network 101
,08-11 12:31:19.887   873  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
,08-11 12:31:19.887   873  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-11 12:31:19.888   873  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,08-11 12:31:19.889   873  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,08-11 12:31:19.889   873  1306 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,08-11 12:31:19.905   873  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-11 12:31:19.914   873  1306 D ConnectivityService: scheduleUnvalidatedPrompt 101
,08-11 12:31:19.914   873  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,08-11 12:31:19.915   873  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
08-11 12:31:19.915   873  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
08-11 12:31:19.915   873  1306 D ConnectivityService:    accepting network in place of null
08-11 12:31:19.915   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 12:31:19.916   873  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 12:31:19.927   873  4275 D NetlinkSocketObserver: NeighborEvent{elapsedMs=363147, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 12:31:19.954   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 12:31:19.982   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 12:31:19.991   873  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-11 12:31:19.991   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:31:20.000   873   890 D Tethering: MasterInitialState.processMessage what=3
08-11 12:31:20.003   873  4272 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.142,2a00:1450:4001:816::200e
08-11 12:31:20.009  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:20.009  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:31:20.009  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:20.009  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:20.013  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:20.013  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:31:20.013  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:20.013  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:20.016  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:20.016  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:20.016  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:20.016  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:20.016  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:20.016  4017  4017 V i,o.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:20.016  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:20.016  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:20.016  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:31:19.998   873  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-11 12:31:20.016  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:20.016  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:31:20.027  1852  1852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 12:31:20.038  1852  1852 D SystemUpdateService: onCreate
,08-11 12:31:20.041  1852  1852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 12:31:20.061  1852  4285 I SystemUpdateService: active receiver: enabled
,08-11 12:31:20.064  1852  1852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-11 12:31:20.071  1852  2387 I iu.UploadsManager: num queued entries: 0
,08-11 12:31:20.072  1852  2387 I iu.UploadsManager: num updated entries: 0
,08-11 12:31:20.074  1852  1852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 12:31:20.075  1852  1852 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 12:31:20.078  4170  4170 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:31:20.084   873  4272 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 10:31:20 GMT], X-Android-Received-Millis=[1470911480083], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470911480055]}
,08-11 12:31:20.086   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 12:31:20.086   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,08-11 12:31:20.086   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,08-11 12:31:20.087  1852  4288 I MDM     : [217] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-11 12:31:20.087  1852  4288 W BaseAppContext: Using Auth Proxy for data requests.
,08-11 12:31:20.089   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-11 12:31:20.090  4170  4170 D SprintDMHelper: simOperator: 
,08-11 12:31:20.090  4170  4170 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 12:31:20.097  1852  4285 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 12:31:20.098  1852  4288 V GoogleAuthProtoRequest: [217] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 12:31:20.111  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:31:20.116  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:31:20.117  1852  2387 I iu.SyncManager: NEXT; no task,
,08-11 12:31:20.118  1852  4285 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-11 12:31:20.118  1852  4285 I SystemUpdateService: now status is 0 (complete)
08-11 12:31:20.118  1852  4285 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,08-11 12:31:20.118  1852  4285 I SystemUpdateService: file has been verified
,08-11 12:31:20.118  1852  4285 I SystemUpdateService: OTA package size = 12249756
,08-11 12:31:20.159  1852  4285 I SystemUpdateService: showing system update notification
,08-11 12:31:20.206  1852  1852 D SystemUpdateService: onDestroy
,08-11 12:31:20.211  1492  1880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-11 12:31:20.211  1492  1880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
,08-11 12:31:20.211  1492  1880 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:31:20.211  1492  1880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:31:20.224  1852  4288 E MDM     : [217] SitrepService.a: Error sending sitrep.
,08-11 12:31:20.260  4128  4291 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-11 12:31:20.992   873  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-11 12:31:22.532   873  1732 D WifiService: setWifiEnabled: false pid=4017, uid=10000
,08-11 12:31:22.532   873  1732 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:31:22.565  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-11 12:31:22.570   873  1304 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-11 12:31:22.570   873  1304 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-11 12:31:22.570   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 12:31:22.570   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 12:31:22.588   873  1304 E native  : do suspend true
,08-11 12:31:22.599   873  2140 D DhcpClient: Clearing IP address
,08-11 12:31:22.599   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-11 12:31:22.602   371   871 D CommandListener: Setting iface cfg
,08-11 12:31:22.606  1492  4295 V NativeCrypto: Read error: ssl=0x9ad33200: I/O error during system call, Connection timed out
,08-11 12:31:22.608  1492  4295 V NativeCrypto: SSL shutdown failed: ssl=0x9ad33200: I/O error during system call, Broken pipe
,08-11 12:31:22.613   873  1733 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,08-11 12:31:22.614   873  4272 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,08-11 12:31:22.620   873  4272 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,08-11 12:31:22.620   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-11 12:31:22.621   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation failed
08-11 12:31:22.621   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-11 12:31:22.628   873  1304 D WifiStateMachine: Start Disconnecting Watchdog 2
08-11 12:31:22.628   398   398 E Parcel  : Reading a NULL string not supported here.
08-11 12:31:22.629   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 12:31:22.629   873  1304 E native  : do suspend true
,08-11 12:31:22.632   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-11 12:31:22.632   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,08-11 12:31:22.642   873  1306 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,08-11 12:31:22.643   873  4276 D DhcpClient: Receive thread stopped
,08-11 12:31:22.643   371   871 D CommandListener: Clearing all IP addresses on wlan0
,08-11 12:31:22.647   873  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 12:31:22.663   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 12:31:22.666  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:22.666  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:22.666  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:22.665  1821  2057 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 12:31:22.666  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:22.667  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:22.667  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:22.667  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:22.668  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:22.668  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:22.668  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:22.668  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:22.669  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:22.670   873  1304 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-11 12:31:22.677   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 12:31:22.705   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 12:31:22.707   873  1306 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,08-11 12:31:22.707   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:31:22.710   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-11 12:31:22.714  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:22.720  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:22.721  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:22.727  1852  1852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
08-11 12:31:22.733  1852  1852 D SystemUpdateService: onCreate
,08-11 12:31:22.737  1852  1852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 12:31:22.749  1852  1852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
08-11 12:31:22.752  1852  2387 I iu.UploadsManager: num queued entries: 0
08-11 12:31:22.752  1852  2387 I iu.UploadsManager: num updated entries: 0
,08-11 12:31:22.757  1852  2387 I iu.SyncManager: NEXT; no task
,08-11 12:31:22.758  1852  4307 I SystemUpdateService: active receiver: enabled
,08-11 12:31:22.760  1852  1852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 12:31:22.761  1852  1852 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
08-11 12:31:22.764  4170  4170 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:31:22.769  1852  4307 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 12:31:22.772  1852  4307 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,08-11 12:31:22.772  1852  4307 I SystemUpdateService: now status is 0 (complete)
08-11 12:31:22.772  1852  4307 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 12:31:22.772  1852  4307 I SystemUpdateService: file has been verified
08-11 12:31:22.773  1852  4307 I SystemUpdateService: OTA package size = 12249756
,08-11 12:31:22.789  4170  4170 D SprintDMHelper: simOperator: 
,08-11 12:31:22.790  4170  4170 D SprintDMReceiver: Not Sprint UICC, don't do anything.
08-11 12:31:22.790   371   871 E Netd    : netlink response contains error (No such file or directory)
,08-11 12:31:22.793   873  1306 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-11 12:31:22.793   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 12:31:22.810  1852  4307 I SystemUpdateService: showing system update notification
,08-11 12:31:22.817  4128  4312 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-11 12:31:22.840  1852  1852 D SystemUpdateService: onDestroy
,08-11 12:31:27.570   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a6c0539:true
,08-11 12:31:27.571  4156  4156 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 12:31:27.575  4156  4156 I bt_bluedroid: init
,08-11 12:31:27.576  4156  4314 I BluetoothAdapterState: Entering OffState
,08-11 12:31:27.581  4156  4315 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-11 12:31:27.582  4156  4315 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 12:31:27.582  4156  4315 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 12:31:27.582  4156  4315 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-11 12:31:27.584  4156  4156 I bt_bluedroid: get_profile_interface socket
08-11 12:31:27.586  4156  4156 I bt_bluedroid: get_profile_interface sdp
,08-11 12:31:27.590  4156  4318 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
08-11 12:31:27.591  4156  4166 I bt_bluedroid: config_hci_snoop_log
,08-11 12:31:27.593   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
08-11 12:31:27.594  4156  4318 D BluetoothAdapterProperties: Name is: Nexus 6
08-11 12:31:27.602  4156  4314 D BluetoothAdapterState: Current state: OFF, message: 0
,08-11 12:31:27.603  4156  4314 D BluetoothAdapterProperties: Setting state to 14
08-11 12:31:27.603  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-11 12:31:27.607  4156  4314 D BluetoothBondStateMachine: make
,08-11 12:31:27.612  4156  4320 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 12:31:27.623  4156  4156 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 12:31:27.624  4156  4314 I BluetoothAdapterState: Entering PendingCommandState
,08-11 12:31:27.632  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:27.637  4156  4156 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 12:31:27.638  4156  4156 D BtGatt.GattService: Received start request. Starting profile...
08-11 12:31:27.638  4156  4156 D BtGatt.GattService: start()
08-11 12:31:27.639  4156  4156 I bt_bluedroid: get_profile_interface gatt
,08-11 12:31:27.641  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:27.641  4156  4156 D BtGatt.AdvertiseManager: advertise manager created
,08-11 12:31:27.653  4156  4156 V BluetoothAdapterState: isTurningOff()=false
,08-11 12:31:27.653  4156  4156 V BluetoothAdapterState: isTurningOn()=false
,08-11 12:31:27.653  4156  4156 V BluetoothAdapterState: isBleTurningOn()=true
08-11 12:31:27.653  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:27.654  4156  4314 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-11 12:31:27.655  4156  4314 I bt_bluedroid: enable
08-11 12:31:27.655  4156  4315 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-11 12:31:27.656  4156  4315 I bt_hci  : start_up
,08-11 12:31:27.675  4156  4315 I bt_vendor: alloc value 0xb39e9189
08-11 12:31:27.676  4156  4315 I bt_vendor: init
,08-11 12:31:27.676  4156  4315 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,08-11 12:31:27.677  4156  4315 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 12:31:27.785  4156  4315 D bt_hci  : start_up starting async portion
,08-11 12:31:27.786  4156  4324 I bt_hci  : event_finish_startup
08-11 12:31:27.786  4156  4324 I bt_hci_h4: hal_open
,08-11 12:31:27.786  4156  4324 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 12:31:27.793  4156  4324 I bt_userial_vendor: device fd = 51 open
,08-11 12:31:27.827  4156  4324 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 12:31:27.859  4156  4324 D bt_hwcfg: Chipset BCM4354A2
,08-11 12:31:27.859  4156  4324 D bt_hwcfg: Target name = [BCM4354A2]
08-11 12:31:27.860  4156  4324 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 12:31:27.921   873  1306 D ConnectivityService: handlePromptUnvalidated 101
,08-11 12:31:28.702  4156  4324 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 12:31:28.704  4156  4324 D bt_hwcfg: Settlement delay -- 100 ms
,08-11 12:31:28.704  4156  4324 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 12:31:28.821  4156  4324 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-11 12:31:28.822  4156  4324 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 12:31:28.851  4156  4324 I bt_hwcfg: vendor lib fwcfg completed
08-11 12:31:28.851  4156  4324 I bt_vendor: firmware callback
08-11 12:31:28.851  4156  4324 I bt_hci  : firmware_config_callback
,08-11 12:31:28.864  4156  4326 I bt_btu  : btu_task pending for preload complete event
08-11 12:31:28.865  4156  4326 I bt_btu_task: Bluetooth chip preload is complete
08-11 12:31:28.865  4156  4326 I bt_btu  : btu_task received preload complete event
,08-11 12:31:28.875  4156  4326 I         : BTE_InitTraceLevels -- TRC_HCI
08-11 12:31:28.875  4156  4326 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-11 12:31:28.876  4156  4326 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-11 12:31:28.876  4156  4326 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-11 12:31:28.876  4156  4326 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 12:31:28.877  4156  4326 I         : BTE_InitTraceLevels -- TRC_A2D,
08-11 12:31:28.877  4156  4326 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-11 12:31:28.877  4156  4326 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 12:31:28.877  4156  4326 I         : BTE_InitTraceLevels -- TRC_GAP
,08-11 12:31:28.878  4156  4326 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 12:31:28.878  4156  4326 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 12:31:28.878  4156  4326 I         : BTE_InitTraceLevels -- TRC_GATT
,08-11 12:31:28.879  4156  4326 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 12:31:28.879  4156  4326 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 12:31:28.879  4156  4326 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 12:31:29.025  4156  4326 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3966d9d
,08-11 12:31:29.025  4156  4326 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3966d9d 
,08-11 12:31:29.042  4156  4318 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 12:31:29.044  4156  4318 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-11 12:31:29.045  4156  4318 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 12:31:29.048  4156  4318 D BluetoothAdapterProperties: Name is: Nexus 6
08-11 12:31:29.050  4156  4318 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:31:29.050  4156  4318 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-11 12:31:29.050  4156  4318 D bt_hci  : do_postload posting postload work item
08-11 12:31:29.051  4156  4324 I bt_hci  : event_postload
,08-11 12:31:29.051  4156  4324 I bt_vendor: sco_config_cb
08-11 12:31:29.051  4156  4324 I bt_hci  : sco_config_callback postload finished.
,08-11 12:31:29.052  4156  4318 D bt_bte_conf: Device ID record 1 : primary
08-11 12:31:29.052  4156  4318 D bt_bte_conf:   vendorId            = 000f
08-11 12:31:29.052  4156  4318 D bt_bte_conf:   vendorIdSource      = 0001
08-11 12:31:29.052  4156  4318 D bt_bte_conf:   product             = 1200
08-11 12:31:29.052  4156  4318 D bt_bte_conf:   version             = 1436
08-11 12:31:29.052  4156  4318 D bt_bte_conf:   clientExecutableURL = 
08-11 12:31:29.052  4156  4318 D bt_bte_conf:   serviceDescription  = 
08-11 12:31:29.052  4156  4318 D bt_bte_conf:   documentationURL    = 
08-11 12:31:29.052  4156  4318 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-11 12:31:29.055  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.053  4156  4315 D bt_stack_manager: event_start_up_stack finished
,08-11 12:31:29.056  4156  4314 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 12:31:29.056  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.057  4156  4314 D BluetoothAdapterProperties: Setting state to 15
08-11 12:31:29.057  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-11 12:31:29.058  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.060  4156  4314 I BluetoothAdapterState: Entering BleOnState
08-11 12:31:29.062  4156  4314 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-11 12:31:29.062  4156  4314 D BluetoothAdapterProperties: Setting state to 11
08-11 12:31:29.062  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-11 12:31:29.063  4156  4324 I bt_vendor: low_power_mode_cb
,08-11 12:31:29.067  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:29.067  4156  4156 D HeadsetService: Received start request. Starting profile...
08-11 12:31:29.071  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.073  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.073  4156  4156 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-11 12:31:29.074  4156  4156 D HeadsetStateMachine: make
08-11 12:31:29.075  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:29.083  4156  4156 D HeadsetStateMachine: max_hf_connections = 1
,08-11 12:31:29.083  4156  4156 I bt_bluedroid: get_profile_interface handsfree
08-11 12:31:29.084  4156  4318 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-11 12:31:29.084  4156  4318 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-11 12:31:29.089  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
08-11 12:31:29.090  4156  4314 I BluetoothAdapterState: Entering PendingCommandState
08-11 12:31:29.090  4156  4156 D A2dpService: Received start request. Starting profile...
,08-11 12:31:29.091  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 12:31:29.091  4156  4156 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 12:31:29.091  4156  4156 I bt_bluedroid: get_profile_interface avrcp
,08-11 12:31:29.098  4156  4156 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-11 12:31:29.099  4156  4156 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-11 12:31:29.099  4156  4156 D A2dpStateMachine: make
08-11 12:31:29.100  4156  4156 I bt_bluedroid: get_profile_interface a2dp
,08-11 12:31:29.101  4156  4318 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 12:31:29.102  4156  4336 D A2dpStateMachine: Enter Disconnected: -2
,08-11 12:31:29.104  4156  4156 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 12:31:29.105  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
08-11 12:31:29.107  4075  4075 D BluetoothInputDevice: Proxy object connected
,08-11 12:31:29.108  4075  4075 D HidProfile: Bluetooth service connected
08-11 12:31:29.108  4156  4156 D HidService: Received start request. Starting profile...
08-11 12:31:29.108  4156  4156 I bt_bluedroid: get_profile_interface hidhost
08-11 12:31:29.108  4156  4156 D HidService: setHidService(): set to: null
08-11 12:31:29.108  4156  4318 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39483e5
08-11 12:31:29.108  4156  4318 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-11 12:31:29.109  4156  4156 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-11 12:31:29.110  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
08-11 12:31:29.111  4156  4156 D HealthService: Received start request. Starting profile...
,08-11 12:31:29.112  4156  4156 I bt_bluedroid: get_profile_interface health
,08-11 12:31:29.114  4156  4333 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-11 12:31:29.114  4156  4156 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:29.114  4156  4156 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:29.114  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:29.114  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:29.117  4156  4156 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-11 12:31:29.118  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:29.119  4156  4156 D PanService: Received start request. Starting profile...
08-11 12:31:29.119  4075  4075 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 12:31:29.120  4156  4156 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 12:31:29.120  4156  4156 I bt_bluedroid: get_profile_interface pan
,08-11 12:31:29.121  4156  4318 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 12:31:29.121  4075  4075 D PanProfile: Bluetooth service connected
,08-11 12:31:29.122  4156  4156 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:29.124  4156  4156 D BluetoothMapService: Received start request. Starting profile...
,08-11 12:31:29.124  4156  4156 D BluetoothMapService: start()
,08-11 12:31:29.124  4075  4075 D BluetoothMap: Proxy object connected
08-11 12:31:29.125  4075  4075 D MapProfile: Bluetooth service connected
,08-11 12:31:29.125  4075  4075 D BluetoothMap: getConnectedDevices()
08-11 12:31:29.126  4156  4156 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-11 12:31:29.127  4075  4075 D BluetoothMap: Bluetooth is Not enabled
,08-11 12:31:29.128  4156  4156 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-11 12:31:29.128  4156  4156 D BluetoothMapAppObserver: createReceiver()
08-11 12:31:29.129  4156  4156 D BluetoothMapAppObserver: initObservers()
,08-11 12:31:29.129  4156  4156 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 12:31:29.135  4156  4156 V BluetoothAdapterState: isTurningOff()=false
,08-11 12:31:29.135  4156  4156 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:29.135  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:29.136  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
,08-11 12:31:29.137  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:29.138  4156  4314 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 12:31:29.138  4156  4314 D BluetoothAdapterProperties: ScanMode =  20
08-11 12:31:29.138  4156  4314 D BluetoothAdapterProperties: State =  11
,08-11 12:31:29.139  4156  4318 D BluetoothAdapterProperties: Scan Mode:21
08-11 12:31:29.139  4156  4318 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 12:31:29.139  4156  4314 D BluetoothAdapterProperties: Setting state to 12
08-11 12:31:29.139  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-11 12:31:29.140  4156  4314 I BluetoothAdapterState: Entering OnState
08-11 12:31:29.140  1354  1370 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:29.143  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:29.144  1354  1374 D BluetoothPbap: onBluetoothStateChange: up=true
08-11 12:31:29.145  1354  1354 D BluetoothA2dp: Proxy object connected
08-11 12:31:29.146  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:29.146   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:31:29.146  4075  4089 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 12:31:29.148  1354  1826 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:31:29.149  1708  1996 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:29.150  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:29.150  1354  1370 D BluetoothMap: onBluetoothStateChange: up=true
,08-11 12:31:29.152  1354  1354 D BluetoothMap: Proxy object connected
,08-11 12:31:29.153  1354  1354 D MapProfile: Bluetooth service connected
08-11 12:31:29.153  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:29.153  1354  1354 D BluetoothMap: getConnectedDevices()
,08-11 12:31:29.154  4075  4086 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 12:31:29.155  4075  4088 D BluetoothMap: onBluetoothStateChange: up=true
08-11 12:31:29.155  4156  4156 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-11 12:31:29.156  1354  1826 D BluetoothPan: onBluetoothStateChange on: true
08-11 12:31:29.156  4156  4156 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-11 12:31:29.158  4156  4156 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:31:29.158  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
,08-11 12:31:29.158  1354  1354 D PanProfile: Bluetooth service connected
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:29.158  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:29.158   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 12:31:29.159   873   873 D BluetoothA2dp: Proxy object connected
,08-11 12:31:29.160  1354  1370 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-11 12:31:29.161  4156  4156 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:31:29.162  1354  1354 D BluetoothInputDevice: Proxy object connected
08-11 12:31:29.162  1354  1354 D HidProfile: Bluetooth service connected
08-11 12:31:29.162  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:29.163  4075  4089 D BluetoothPan: onBluetoothStateChange on: true
,08-11 12:31:29.164   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:31:29.164   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:31:29.164  4156  4156 D ObexServerSockets: Succeed to create listening sockets 
08-11 12:31:29.164  4156  4156 D ObexServerSockets0: startAccept()
,08-11 12:31:29.164  4156  4156 D ObexServerSockets0: prepareForNewConnect()
08-11 12:31:29.165   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 12:31:29.166  4156  4156 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-11 12:31:29.166  4156  4156 D BluetoothSdpJni: SDP Create record success - handle: 0
08-11 12:31:29.167  4156  4156 D BluetoothMapService: onReceive
,08-11 12:31:29.167  4156  4156 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:31:29.167  4156  4156 D BluetoothMapService: STATE_ON
,08-11 12:31:29.168  4156  4342 D ObexServerSockets0: Accepting socket connection...
08-11 12:31:29.168  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.168  4156  4341 D ObexServerSockets0: Accepting socket connection...
08-11 12:31:29.170  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.171  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:29.173  4075  4075 D LocalBluetoothProfileManager: Adding local A2DP profile
08-11 12:31:29.178  4075  4075 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-11 12:31:29.185  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 12:31:29.188  4156  4156 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 12:31:29.188  4156  4156 D ObexServerSockets0: prepareForNewConnect()
,08-11 12:31:29.188  4075  4075 D BluetoothA2dp: Proxy object connected
,08-11 12:31:29.199  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 12:31:29.201  1354  1354 D BluetoothPbap: Proxy object connected
08-11 12:31:29.201  1354  1354 D PbapServerProfile: Bluetooth service connected
,08-11 12:31:29.203  4156  4344 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 12:31:29.207  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,08-11 12:31:29.208  4075  4075 D BluetoothPbap: Proxy object connected
08-11 12:31:29.208  4075  4075 D PbapServerProfile: Bluetooth service connected
,08-11 12:31:29.239  4156  4351 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 12:31:29.240  4156  4351 I BtOppRfcommListener: Accept thread started.
,08-11 12:31:29.247   873   873 D BluetoothHeadset: Proxy object connected
08-11 12:31:29.247   873   873 D BluetoothHeadset: Proxy object connected
,08-11 12:31:29.248  1354  1374 D BluetoothHeadset: Proxy object connected
08-11 12:31:29.248  1354  1354 D HeadsetProfile: Bluetooth service connected
08-11 12:31:29.249  1708  1995 D BluetoothHeadset: Proxy object connected
,08-11 12:31:29.249   873   873 D BluetoothHeadset: Proxy object connected
08-11 12:31:29.250  1354  1370 D BluetoothHeadset: Proxy object connected
08-11 12:31:29.251  1708  1729 D BluetoothHeadset: Proxy object connected
08-11 12:31:29.251  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-11 12:31:29.264   873   890 D BluetoothHeadset: Proxy object connected
,08-11 12:31:29.264   873   890 D BluetoothHeadset: Proxy object connected
,08-11 12:31:29.280  4075  4089 D BluetoothHeadset: Proxy object connected
08-11 12:31:29.281  4075  4075 D HeadsetProfile: Bluetooth service connected
,08-11 12:31:29.332  1650  1752 I Keyboard.Facilitator.LanguageModelFlusher: run()
,08-11 12:31:29.332  1650  1752 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-11 12:31:29.355  1492  1492 I ConfigService: onCreate
,08-11 12:31:32.550  4156  4314 D BluetoothAdapterState: Current state: ON, message: 23
,08-11 12:31:32.550  4156  4314 D BluetoothAdapterProperties: Setting state to 13
,08-11 12:31:32.550  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-11 12:31:32.552  4156  4314 D BluetoothAdapterProperties: onBluetoothDisable()
,08-11 12:31:32.557  4156  4314 I BluetoothAdapterState: Entering PendingCommandState
,08-11 12:31:32.563  4156  4156 D BluetoothMapService: onReceive
,08-11 12:31:32.563  4156  4156 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,08-11 12:31:32.564  4156  4156 D BluetoothMapService: STATE_TURNING_OFF
,08-11 12:31:32.567  4156  4156 D BluetoothMapService: MAP Service closeService in
08-11 12:31:32.567  4156  4156 D BluetoothMapMasInstance0: MAP Service shutdown
08-11 12:31:32.567  4156  4156 D ObexServerSockets0: shutdown(block = true)
08-11 12:31:32.570  4156  4341 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,08-11 12:31:32.576  4156  4318 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:31:32.577  4156  4314 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-11 12:31:32.580  4156  4156 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 12:31:32.580  4156  4342 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-11 12:31:32.581  4156  4328 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-11 12:31:32.582  4156  4156 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-11 12:31:32.582  4156  4156 I BtOppRfcommListener: stopping Accept Thread
08-11 12:31:32.582  4156  4351 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-11 12:31:32.583  4156  4351 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-11 12:31:32.583  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:32.583  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:32.585  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:32.585  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:32.585  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 12:31:32.586  4156  4156 D HeadsetService: Received stop request...Stopping profile...
08-11 12:31:32.588  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:32.588  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:32.588  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:32.588  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:32.591  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:32.591  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:32.592  4017  4017 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-11 12:31:32.592  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:32.593   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:32.593   873   873 D BluetoothHeadset: Proxy object disconnected
,08-11 12:31:32.593  1354  1826 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:32.594  4156  4156 D A2dpService: Received stop request...Stopping profile...
08-11 12:31:32.594  4075  4088 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:32.594  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:32.594  1708  1727 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:32.595   873   873 D BluetoothHeadset: Proxy object disconnected
08-11 12:31:32.595  4156  4336 D A2dpStateMachine: Exit Disconnected: -1
08-11 12:31:32.595  4075  4075 D DockEventReceiver: finishStartingService: stopping service
08-11 12:31:32.596  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:32.597   873   873 D BluetoothA2dp: Proxy object disconnected
08-11 12:31:32.599  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:32.599  4075  4075 D HeadsetProfile: Bluetooth service disconnected
08-11 12:31:32.600  4075  4075 D BluetoothA2dp: Proxy object disconnected
08-11 12:31:32.601  1354  1354 D HeadsetProfile: Bluetooth service disconnected
08-11 12:31:32.601  4156  4156 D HidService: Received stop request...Stopping profile...
08-11 12:31:32.601  4156  4156 D HidService: Stopping Bluetooth HidService
,08-11 12:31:32.601  1354  1354 D BluetoothA2dp: Proxy object disconnected
08-11 12:31:32.602  4075  4075 D BluetoothInputDevice: Proxy object disconnected
08-11 12:31:32.602  1354  1354 D BluetoothInputDevice: Proxy object disconnected
08-11 12:31:32.603  4156  4156 D HealthService: Received stop request...Stopping profile...
08-11 12:31:32.603  1354  1354 D HidProfile: Bluetooth service disconnected
,08-11 12:31:32.604  4075  4075 D HidProfile: Bluetooth service disconnected
08-11 12:31:32.604  4156  4156 D PanService: Received stop request...Stopping profile...
08-11 12:31:32.605  4075  4075 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-11 12:31:32.605  4075  4075 D PanProfile: Bluetooth service disconnected
,08-11 12:31:32.606  1354  1354 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-11 12:31:32.606  1354  1354 D PanProfile: Bluetooth service disconnected
08-11 12:31:32.607  4156  4156 D BluetoothMapService: Received stop request...Stopping profile...
08-11 12:31:32.607  4156  4156 D BluetoothMapService: stop()
,08-11 12:31:32.608  4156  4156 D BluetoothMapAppObserver: deinitObservers()
08-11 12:31:32.609  4156  4156 D BluetoothMapAppObserver: removeReceiver()
08-11 12:31:32.609  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 12:31:32.612  4075  4075 D BluetoothMap: Proxy object disconnected
08-11 12:31:32.612  4075  4075 D MapProfile: Bluetooth service disconnected
08-11 12:31:32.612  1354  1354 D BluetoothMap: Proxy object disconnected
08-11 12:31:32.612  4156  4156 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:32.612  1354  1354 D MapProfile: Bluetooth service disconnected
08-11 12:31:32.612  4156  4156 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:32.612  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:32.612  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:32.613  4156  4156 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:32.613  4156  4156 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:32.613  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:32.613  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:32.614  4156  4156 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-11 12:31:32.614  4156  4326 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:32.614  4156  4326 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:32.614  4156  4326 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:32.615  4156  4318 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,08-11 12:31:32.615  4156  4318 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,08-11 12:31:32.615  4156  4156 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-11 12:31:32.616  4156  4326 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:32.617  4156  4326 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-11 12:31:32.617  4156  4326 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:31:32.617  4156  4326 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:31:32.617  4156  4326 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-11 12:31:32.617  4156  4326 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-11 12:31:32.617  4156  4318 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,08-11 12:31:32.618  4156  4156 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:32.618  4156  4156 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:32.618  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:32.618  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:32.619  4156  4156 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-11 12:31:32.619  4156  4318 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 12:31:32.619  4156  4156 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-11 12:31:32.620  4156  4156 V BluetoothAdapterState: isTurningOff()=true
,08-11 12:31:32.620  4156  4156 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:32.620  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:32.620  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:32.620  4156  4156 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-11 12:31:32.621  4156  4318 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-11 12:31:32.621  4156  4156 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-11 12:31:32.621  4156  4156 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:32.621  4156  4156 V BluetoothAdapterState: isTurningOn()=false
,08-11 12:31:32.621  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:32.621  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:32.622  4156  4156 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-11 12:31:32.622  4156  4156 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-11 12:31:32.624  4075  4075 D BluetoothPbap: Proxy object disconnected
08-11 12:31:32.624  4075  4075 D PbapServerProfile: Bluetooth service disconnected
,08-11 12:31:32.625  1354  1354 D BluetoothPbap: Proxy object disconnected
08-11 12:31:32.625  4156  4156 D BluetoothMapService: MAP Service closeService in
08-11 12:31:32.625  1354  1354 D PbapServerProfile: Bluetooth service disconnected
08-11 12:31:32.625  4156  4156 V BluetoothAdapterState: isTurningOff()=true
08-11 12:31:32.625  4156  4156 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:32.625  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:32.625  4156  4156 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:32.626  4156  4314 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,08-11 12:31:32.626  4156  4314 D BluetoothAdapterProperties: Setting state to 15
08-11 12:31:32.626  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-11 12:31:32.626  4156  4314 I BluetoothAdapterState: Entering BleOnState
08-11 12:31:32.627  1354  1370 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-11 12:31:32.628  4156  4156 D BluetoothMapService: cleanup()
,08-11 12:31:32.628  4156  4156 D BluetoothMapService: MAP Service closeService in
08-11 12:31:32.629  1354  1826 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 12:31:32.630   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 12:31:32.631  4075  4089 D BluetoothPbap: onBluetoothStateChange: up=false
08-11 12:31:32.632  1354  1374 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:31:32.632  1708  1996 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:31:32.632  1354  1370 D BluetoothMap: onBluetoothStateChange: up=false
,08-11 12:31:32.633  4075  4086 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-11 12:31:32.634  4075  4088 D BluetoothMap: onBluetoothStateChange: up=false
,08-11 12:31:32.634  4075  4089 D BluetoothHeadset: onBluetoothStateChange: up=false
08-11 12:31:32.635  1354  1826 D BluetoothPan: onBluetoothStateChange on: false
08-11 12:31:32.635   873   890 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-11 12:31:32.635  1354  1374 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-11 12:31:32.636  4075  4086 D BluetoothA2dp: onBluetoothStateChange: up=false
08-11 12:31:32.636  4075  4088 D BluetoothPan: onBluetoothStateChange on: false
,08-11 12:31:32.637   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-11 12:31:32.637   873   890 D BluetoothHeadset: onBluetoothStateChange: up=false,
08-11 12:31:32.637  4156  4314 D BluetoothAdapterState: Current state: BLE ON, message: 20
,08-11 12:31:32.637  4156  4314 D BluetoothAdapterProperties: Setting state to 16
08-11 12:31:32.637  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-11 12:31:32.638  4156  4314 D BluetoothAdapterProperties: onBleDisable
08-11 12:31:32.639  4156  4314 I BluetoothAdapterState: Entering PendingCommandState
08-11 12:31:32.639  4156  4315 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-11 12:31:32.640  4156  4326 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-11 12:31:32.640  4156  4326 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-11 12:31:32.641  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:32.642  4156  4318 D BluetoothAdapterProperties: Scan Mode:20
08-11 12:31:32.642  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-11 12:31:32.643  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:32.644  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:32.646  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:32.648  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:32.648  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:31:32.649  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:32.650  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,08-11 12:31:32.845  4156  4318 I bt_hci  : shut_down
,08-11 12:31:32.847  4156  4324 D bt_hwcfg: hw_epilog_process
,08-11 12:31:32.848  4156  4324 I bt_vendor: low_power_mode_cb
,08-11 12:31:32.868  4156  4324 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-11 12:31:32.869  4156  4324 I bt_vendor: epilog_cb
08-11 12:31:32.869  4156  4324 I bt_hci  : epilog_finished_callback
,08-11 12:31:32.881  4156  4318 I bt_hci_h4: hal_close
,08-11 12:31:32.884  4156  4318 I bt_userial_vendor: device fd = 51 close
,08-11 12:31:33.010  4156  4315 D bt_stack_manager: event_shut_down_stack finished.
,08-11 12:31:33.011  4156  4314 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-11 12:31:33.018  4156  4156 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-11 12:31:33.019  4156  4314 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-11 12:31:33.020  4156  4156 D BtGatt.GattService: Received stop request...Stopping profile...
,08-11 12:31:33.020  4156  4156 D BtGatt.GattService: stop()
08-11 12:31:33.021  4156  4156 D BtGatt.AdvertiseManager: advertise clients cleared
,08-11 12:31:33.027  4156  4156 V BluetoothAdapterState: isTurningOff()=false
,08-11 12:31:33.027  4156  4156 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:33.027  4156  4156 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:33.028  4156  4156 V BluetoothAdapterState: isBleTurningOff()=true
,08-11 12:31:33.028  4156  4314 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-11 12:31:33.029  4156  4314 D BluetoothAdapterProperties: Setting state to 10
08-11 12:31:33.029  4156  4314 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-11 12:31:33.031  4156  4314 I BluetoothAdapterState: Entering OffState
,08-11 12:31:33.034   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-11 12:31:33.057  4156  4156 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-11 12:31:33.058  4156  4156 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-11 12:31:33.058  4156  4315 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,08-11 12:31:33.064  4156  4315 D bt_stack_manager: event_clean_up_stack finished.
,08-11 12:31:33.065  4156  4156 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-11 12:31:33.072  4156  4156 I art     : System.exit called, status: 0
,08-11 12:31:33.072  4156  4156 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-11 12:31:33.125   873  1733 I ActivityManager: Process com.android.bluetooth (pid 4156) has died
,08-11 12:31:34.419  1492  1492 I ConfigService: onDestroy
,08-11 12:31:37.547  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:37.548  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:42.554  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:42.554  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fd86f49 removed from the list
08-11 12:31:42.555  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:42.555  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:42.555  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:42.559  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 12:31:42.560  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c5a56f added. We now have 4 listener(s)
08-11 12:31:42.560  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:31:42.563  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:42.565  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4c5a56f removed from the list
08-11 12:31:42.565  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:42.566  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:42.567  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:42.570  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 12:31:42.571  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@369727c added. We now have 4 listener(s)
08-11 12:31:42.571  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:31:42.573  4017  4063 I System.out: IsBluetoothEnabled
,08-11 12:31:42.585  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:42.635   873   890 I ActivityManager: Start proc 4362:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-11 12:31:42.782  4362  4362 D AdapterServiceConfig: Adding HeadsetService
08-11 12:31:42.782  4362  4362 D AdapterServiceConfig: Adding A2dpService
,08-11 12:31:42.782  4362  4362 D AdapterServiceConfig: Adding HidService
,08-11 12:31:42.783  4362  4362 D AdapterServiceConfig: Adding HealthService
08-11 12:31:42.783  4362  4362 D AdapterServiceConfig: Adding PanService
08-11 12:31:42.783  4362  4362 D AdapterServiceConfig: Adding GattService
08-11 12:31:42.784  4362  4362 D AdapterServiceConfig: Adding BluetoothMapService
,08-11 12:31:42.803   873   890 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7c612f9:true
,08-11 12:31:42.804  4362  4362 D BluetoothAdapterState: make() - Creating AdapterState
,08-11 12:31:42.812  4362  4362 I bt_bluedroid: init
,08-11 12:31:42.812  4362  4374 I BluetoothAdapterState: Entering OffState
,08-11 12:31:42.816  4362  4375 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-11 12:31:42.816  4362  4375 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-11 12:31:42.816  4362  4375 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-11 12:31:42.816  4362  4375 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-11 12:31:42.818  4362  4362 I bt_bluedroid: get_profile_interface socket
,08-11 12:31:42.823  4362  4362 I bt_bluedroid: get_profile_interface sdp
,08-11 12:31:42.823  4362  4378 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 12:31:42.827  4362  4378 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 12:31:42.830  4362  4373 I bt_bluedroid: config_hci_snoop_log
,08-11 12:31:42.832   873   890 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-11 12:31:42.844  4362  4374 D BluetoothAdapterState: Current state: OFF, message: 0
08-11 12:31:42.844  4362  4374 D BluetoothAdapterProperties: Setting state to 14
,08-11 12:31:42.844  4362  4374 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
08-11 12:31:42.846  4362  4374 D BluetoothBondStateMachine: make
,08-11 12:31:42.852  4362  4379 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-11 12:31:42.855  4362  4374 I BluetoothAdapterState: Entering PendingCommandState
,08-11 12:31:42.860  4362  4362 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-11 12:31:42.868  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:42.870  4362  4362 D BtGatt.DebugUtils: handleDebugAction() action=null
08-11 12:31:42.872  4362  4362 D BtGatt.GattService: Received start request. Starting profile...
,08-11 12:31:42.872  4362  4362 D BtGatt.GattService: start()
08-11 12:31:42.872  4362  4362 I bt_bluedroid: get_profile_interface gatt
08-11 12:31:42.875  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:42.875  4362  4362 D BtGatt.AdvertiseManager: advertise manager created
,08-11 12:31:42.883  4362  4362 V BluetoothAdapterState: isTurningOff()=false
,08-11 12:31:42.883  4362  4362 V BluetoothAdapterState: isTurningOn()=false
08-11 12:31:42.883  4362  4362 V BluetoothAdapterState: isBleTurningOn()=true
08-11 12:31:42.883  4362  4362 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:42.884  4362  4374 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-11 12:31:42.884  4362  4374 I bt_bluedroid: enable
,08-11 12:31:42.885  4362  4375 D bt_stack_manager: event_start_up_stack is bringing up the stack.
08-11 12:31:42.885  4362  4375 I bt_hci  : start_up
,08-11 12:31:42.896  4362  4375 I bt_vendor: alloc value 0xb3a3a189
08-11 12:31:42.896  4362  4375 I bt_vendor: init
08-11 12:31:42.896  4362  4375 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-11 12:31:42.896  4362  4375 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-11 12:31:43.005  4362  4375 D bt_hci  : start_up starting async portion
,08-11 12:31:43.006  4362  4382 I bt_hci  : event_finish_startup
08-11 12:31:43.006  4362  4382 I bt_hci_h4: hal_open
08-11 12:31:43.007  4362  4382 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-11 12:31:43.017  4362  4382 I bt_userial_vendor: device fd = 51 open
,08-11 12:31:43.049  4362  4382 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 12:31:43.080  4362  4382 D bt_hwcfg: Chipset BCM4354A2
,08-11 12:31:43.080  4362  4382 D bt_hwcfg: Target name = [BCM4354A2]
08-11 12:31:43.081  4362  4382 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,08-11 12:31:43.937  4362  4382 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-11 12:31:43.937  4362  4382 D bt_hwcfg: Settlement delay -- 100 ms
08-11 12:31:43.938  4362  4382 I bt_hwcfg: Setting fw settlement delay to 100 
,08-11 12:31:44.054  4362  4382 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-11 12:31:44.055  4362  4382 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,08-11 12:31:44.085  4362  4382 I bt_hwcfg: vendor lib fwcfg completed
,08-11 12:31:44.086  4362  4382 I bt_vendor: firmware callback
08-11 12:31:44.086  4362  4382 I bt_hci  : firmware_config_callback
,08-11 12:31:44.099  4362  4384 I bt_btu  : btu_task pending for preload complete event
,08-11 12:31:44.099  4362  4384 I bt_btu_task: Bluetooth chip preload is complete
08-11 12:31:44.099  4362  4384 I bt_btu  : btu_task received preload complete event
,08-11 12:31:44.110  4362  4384 I         : BTE_InitTraceLevels -- TRC_HCI
,08-11 12:31:44.111  4362  4384 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-11 12:31:44.111  4362  4384 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-11 12:31:44.111  4362  4384 I         : BTE_InitTraceLevels -- TRC_AVDT
08-11 12:31:44.112  4362  4384 I         : BTE_InitTraceLevels -- TRC_AVRC
08-11 12:31:44.112  4362  4384 I         : BTE_InitTraceLevels -- TRC_A2D
08-11 12:31:44.112  4362  4384 I         : BTE_InitTraceLevels -- TRC_BNEP
08-11 12:31:44.112  4362  4384 I         : BTE_InitTraceLevels -- TRC_BTM
08-11 12:31:44.113  4362  4384 I         : BTE_InitTraceLevels -- TRC_GAP
,08-11 12:31:44.113  4362  4384 I         : BTE_InitTraceLevels -- TRC_PAN
08-11 12:31:44.113  4362  4384 I         : BTE_InitTraceLevels -- TRC_SDP
08-11 12:31:44.114  4362  4384 I         : BTE_InitTraceLevels -- TRC_GATT
08-11 12:31:44.114  4362  4384 I         : BTE_InitTraceLevels -- TRC_SMP
08-11 12:31:44.114  4362  4384 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-11 12:31:44.114  4362  4384 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-11 12:31:44.249  4362  4384 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39b7d9d
,08-11 12:31:44.250  4362  4384 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39b7d9d 
,08-11 12:31:44.261  4362  4378 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-11 12:31:44.263  4362  4378 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-11 12:31:44.264  4362  4378 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,08-11 12:31:44.268  4362  4378 D BluetoothAdapterProperties: Name is: Nexus 6
,08-11 12:31:44.273  4362  4378 D BluetoothAdapterProperties: Scan Mode:20
,08-11 12:31:44.274  4362  4378 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-11 12:31:44.275  4362  4378 D bt_hci  : do_postload posting postload work item
,08-11 12:31:44.275  4362  4382 I bt_hci  : event_postload
,08-11 12:31:44.275  4362  4382 I bt_vendor: sco_config_cb
08-11 12:31:44.275  4362  4382 I bt_hci  : sco_config_callback postload finished.
08-11 12:31:44.279  4362  4378 D bt_bte_conf: Device ID record 1 : primary
,08-11 12:31:44.279  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:44.279  4362  4378 D bt_bte_conf:   vendorId            = 000f
08-11 12:31:44.279  4362  4378 D bt_bte_conf:   vendorIdSource      = 0001
08-11 12:31:44.279  4362  4378 D bt_bte_conf:   product             = 1200
08-11 12:31:44.279  4362  4378 D bt_bte_conf:   version             = 1436
,08-11 12:31:44.280  4362  4378 D bt_bte_conf:   clientExecutableURL = 
08-11 12:31:44.280  4362  4378 D bt_bte_conf:   serviceDescription  = 
,08-11 12:31:44.281  4362  4378 D bt_bte_conf:   documentationURL    = 
08-11 12:31:44.281  4362  4378 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-11 12:31:44.282  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:44.282  4362  4375 D bt_stack_manager: event_start_up_stack finished
08-11 12:31:44.283  4362  4382 I bt_vendor: low_power_mode_cb
08-11 12:31:44.284  4362  4374 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-11 12:31:44.284  4362  4374 D BluetoothAdapterProperties: Setting state to 15
08-11 12:31:44.284  4362  4374 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-11 12:31:44.285  4362  4374 I BluetoothAdapterState: Entering BleOnState
08-11 12:31:44.291  4362  4374 D BluetoothAdapterState: Current state: BLE ON, message: 1
08-11 12:31:44.291  4362  4374 D BluetoothAdapterProperties: Setting state to 11
08-11 12:31:44.291  4362  4374 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-11 12:31:44.297  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
08-11 12:31:44.302  4362  4362 D HeadsetService: Received start request. Starting profile...
,08-11 12:31:44.310  4362  4374 I BluetoothAdapterState: Entering PendingCommandState
,08-11 12:31:44.310  4362  4362 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-11 12:31:44.311  4362  4362 D HeadsetStateMachine: make
,08-11 12:31:44.318  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:44.321  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:44.325  4362  4362 D HeadsetStateMachine: max_hf_connections = 1
,08-11 12:31:44.325  4362  4362 I bt_bluedroid: get_profile_interface handsfree
08-11 12:31:44.325  4362  4378 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-11 12:31:44.326  4362  4378 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,08-11 12:31:44.330  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:44.331  4362  4362 D A2dpService: Received start request. Starting profile...
,08-11 12:31:44.332  4362  4362 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-11 12:31:44.332  4362  4362 I bt_bluedroid: get_profile_interface avrcp
,08-11 12:31:44.340  4362  4362 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-11 12:31:44.340  4362  4362 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-11 12:31:44.340  4362  4362 D A2dpStateMachine: make
,08-11 12:31:44.342  4362  4362 I bt_bluedroid: get_profile_interface a2dp
,08-11 12:31:44.343  4362  4378 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-11 12:31:44.344  4362  4393 D A2dpStateMachine: Enter Disconnected: -2
,08-11 12:31:44.344  4362  4362 I BluetoothHidServiceJni: classInitNative: succeeds
,08-11 12:31:44.346  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:44.347  4362  4362 D HidService: Received start request. Starting profile...
,08-11 12:31:44.348  4362  4362 I bt_bluedroid: get_profile_interface hidhost
,08-11 12:31:44.348  4362  4362 D HidService: setHidService(): set to: null
,08-11 12:31:44.348  4362  4378 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39993e5
,08-11 12:31:44.348  4362  4378 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-11 12:31:44.349  4362  4362 I BluetoothHealthServiceJni: classInitNative: succeeds
08-11 12:31:44.350  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
08-11 12:31:44.350  4362  4362 D HealthService: Received start request. Starting profile...
08-11 12:31:44.352  4362  4362 I bt_bluedroid: get_profile_interface health
,08-11 12:31:44.353  4362  4362 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-11 12:31:44.354  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
08-11 12:31:44.355  4362  4362 D PanService: Received start request. Starting profile...
,08-11 12:31:44.355  4362  4362 D BluetoothPanServiceJni: initializeNative(L110): pan
08-11 12:31:44.355  4362  4362 I bt_bluedroid: get_profile_interface pan
08-11 12:31:44.356  4362  4378 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-11 12:31:44.359  4362  4362 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
08-11 12:31:44.360  4362  4362 D BluetoothMapService: Received start request. Starting profile...
08-11 12:31:44.360  4362  4362 D BluetoothMapService: start()
,08-11 12:31:44.365  4362  4362 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-11 12:31:44.367  4362  4362 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-11 12:31:44.367  4362  4362 D BluetoothMapAppObserver: createReceiver()
,08-11 12:31:44.370  4362  4362 D BluetoothMapAppObserver: initObservers()
,08-11 12:31:44.371  4362  4362 D BluetoothMapAppObserver: getEnabledAccountItems()
,08-11 12:31:44.396  4362  4362 V BluetoothAdapterState: isTurningOff()=false
,08-11 12:31:44.396  4362  4362 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:44.396  4362  4362 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:44.397  4362  4362 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:44.397  4362  4390 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,08-11 12:31:44.396  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-11 12:31:44.398  4362  4362 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:44.398  4362  4362 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:44.398  4362  4362 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:44.398  4362  4362 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isTurningOff()=false
,08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isBleTurningOff()=false
,08-11 12:31:44.399  4362  4362 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:44.400  4362  4362 V BluetoothAdapterState: isTurningOn()=true
08-11 12:31:44.400  4362  4362 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:44.400  4362  4362 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:44.400  4362  4362 V BluetoothAdapterState: isTurningOff()=false
08-11 12:31:44.400  4362  4362 V BluetoothAdapterState: isTurningOn()=true
,08-11 12:31:44.400  4362  4362 V BluetoothAdapterState: isBleTurningOn()=false
08-11 12:31:44.400  4362  4362 V BluetoothAdapterState: isBleTurningOff()=false
08-11 12:31:44.401  4362  4374 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-11 12:31:44.401  4362  4374 D BluetoothAdapterProperties: ScanMode =  20
08-11 12:31:44.401  4362  4374 D BluetoothAdapterProperties: State =  11
08-11 12:31:44.401  4362  4374 D BluetoothAdapterProperties: Setting state to 12
08-11 12:31:44.401  4362  4374 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-11 12:31:44.403  4362  4374 I BluetoothAdapterState: Entering OnState
,08-11 12:31:44.407  1354  1826 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-11 12:31:44.412  4362  4362 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-11 12:31:44.413  4362  4362 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-11 12:31:44.416  4362  4378 D BluetoothAdapterProperties: Scan Mode:21
08-11 12:31:44.416  4362  4378 D BluetoothAdapterProperties: Discoverable Timeout:120
08-11 12:31:44.417  1354  1374 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 12:31:44.418  4362  4362 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 12:31:44.419   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:31:44.419  4075  4089 D BluetoothPbap: onBluetoothStateChange: up=true
,08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:44.421  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-11 12:31:44.421  1354  1370 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:31:44.422  1708  1996 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:31:44.422  4362  4362 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-11 12:31:44.423  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-11 12:31:44.423  1354  1826 D BluetoothMap: onBluetoothStateChange: up=true
,08-11 12:31:44.424  4362  4362 D ObexServerSockets: Succeed to create listening sockets 
,08-11 12:31:44.424  4362  4362 D ObexServerSockets0: startAccept()
08-11 12:31:44.424  4362  4362 D ObexServerSockets0: prepareForNewConnect()
08-11 12:31:44.425  4075  4086 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:44.426  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:44.426  4362  4362 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,08-11 12:31:44.427  4362  4362 D BluetoothSdpJni: SDP Create record success - handle: 0
08-11 12:31:44.427  4075  4088 D BluetoothMap: onBluetoothStateChange: up=true
08-11 12:31:44.428  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:44.429  1354  1354 D BluetoothA2dp: Proxy object connected
,08-11 12:31:44.429  4075  4089 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-11 12:31:44.430  4362  4399 D ObexServerSockets0: Accepting socket connection...
,08-11 12:31:44.430  1354  1370 D BluetoothPan: onBluetoothStateChange on: true
,08-11 12:31:44.431  1354  1354 D BluetoothMap: Proxy object connected
,08-11 12:31:44.431  1354  1354 D MapProfile: Bluetooth service connected
,08-11 12:31:44.431  4362  4400 D ObexServerSockets0: Accepting socket connection...
,08-11 12:31:44.431  1354  1354 D BluetoothMap: getConnectedDevices()
,08-11 12:31:44.431  4075  4075 D BluetoothMap: Proxy object connected
08-11 12:31:44.431  4075  4075 D MapProfile: Bluetooth service connected
08-11 12:31:44.431  4075  4075 D BluetoothMap: getConnectedDevices()
08-11 12:31:44.432   873   890 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 12:31:44.432  1354  1374 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-11 12:31:44.432   873   873 D BluetoothA2dp: Proxy object connected
08-11 12:31:44.433  1354  1354 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 12:31:44.433  1354  1354 D PanProfile: Bluetooth service connected
08-11 12:31:44.434  1354  1354 D BluetoothInputDevice: Proxy object connected
08-11 12:31:44.434  1354  1354 D HidProfile: Bluetooth service connected
08-11 12:31:44.434  4075  4089 D BluetoothA2dp: onBluetoothStateChange: up=true
08-11 12:31:44.434  4075  4075 D BluetoothInputDevice: Proxy object connected
08-11 12:31:44.435  4075  4075 D HidProfile: Bluetooth service connected
08-11 12:31:44.436  4075  4088 D BluetoothPan: onBluetoothStateChange on: true
08-11 12:31:44.436  4075  4075 D BluetoothA2dp: Proxy object connected
08-11 12:31:44.437   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:31:44.437   873   890 D BluetoothHeadset: onBluetoothStateChange: up=true
08-11 12:31:44.437  4075  4075 D BluetoothPan: BluetoothPAN Proxy object connected
08-11 12:31:44.438  4075  4075 D PanProfile: Bluetooth service connected
08-11 12:31:44.439  4362  4362 D BluetoothMapService: onReceive
08-11 12:31:44.439   873   873 I Telecom : BluetoothPhoneService: queryPhoneState
08-11 12:31:44.440  4362  4362 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-11 12:31:44.440  4362  4362 D BluetoothMapService: STATE_ON
08-11 12:31:44.441  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:31:44.442  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:44.445  4075  4075 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-11 12:31:44.452  1492  1492 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-11 12:31:44.452  4075  4075 D DockEventReceiver: finishStartingService: stopping service
,08-11 12:31:44.459  4075  4075 D BluetoothPbap: Proxy object connected
,08-11 12:31:44.459  4075  4075 D PbapServerProfile: Bluetooth service connected
,08-11 12:31:44.463  1354  1354 D BluetoothPbap: Proxy object connected
,08-11 12:31:44.463  1354  1354 D PbapServerProfile: Bluetooth service connected
08-11 12:31:44.464  4362  4362 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-11 12:31:44.464  4362  4362 D ObexServerSockets0: prepareForNewConnect()
,08-11 12:31:44.466  4362  4405 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 12:31:44.479  4362  4409 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 12:31:44.480  4362  4409 I BtOppRfcommListener: Accept thread started.
,08-11 12:31:44.521   873   873 D BluetoothHeadset: Proxy object connected
,08-11 12:31:44.521   873   873 D BluetoothHeadset: Proxy object connected
08-11 12:31:44.521  1354  1826 D BluetoothHeadset: Proxy object connected
08-11 12:31:44.522  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-11 12:31:44.522  4075  4086 D BluetoothHeadset: Proxy object connected
08-11 12:31:44.522  1354  1370 D BluetoothHeadset: Proxy object connected
08-11 12:31:44.522  4075  4075 D HeadsetProfile: Bluetooth service connected
,08-11 12:31:44.522  1708  1995 D BluetoothHeadset: Proxy object connected
08-11 12:31:44.523   873   873 D BluetoothHeadset: Proxy object connected
,08-11 12:31:44.524  1708  1729 D BluetoothHeadset: Proxy object connected
,08-11 12:31:44.524  1354  1354 D HeadsetProfile: Bluetooth service connected
,08-11 12:31:44.531  4075  4088 D BluetoothHeadset: Proxy object connected
,08-11 12:31:44.531  4075  4075 D HeadsetProfile: Bluetooth service connected
,08-11 12:31:44.538   873   890 D BluetoothHeadset: Proxy object connected
,08-11 12:31:44.538   873   890 D BluetoothHeadset: Proxy object connected
,08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:44.598  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:44.602  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:44.602  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:44.603  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@369727c removed from the list
,08-11 12:31:44.603  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:44.603  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:44.603  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-11 12:31:44.605  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:31:44.605  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cafb705 added. We now have 4 listener(s)
08-11 12:31:44.606  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:31:44.610   873   883 D WifiService: setWifiEnabled: false pid=4017, uid=10000
08-11 12:31:44.610   873   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:31:44.619  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:44.620   873  1733 D WifiService: setWifiEnabled: true pid=4017, uid=10000
,08-11 12:31:44.620   873  1733 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-11 12:31:44.634   873  1304 D WifiConfigStore: Loading config and enabling all networks 
,08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:44.645  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:44.651  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:44.657  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:44.662  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:44.665   873  1304 D WifiConfigStore: loaded 0 passpoint configs
,08-11 12:31:44.666   873  1304 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
08-11 12:31:44.667   873  1304 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,08-11 12:31:44.668   873  1304 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-11 12:31:44.668   873  1304 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
08-11 12:31:44.668   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
08-11 12:31:44.668   873  1304 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-11 12:31:44.680   371   871 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-11 12:31:44.681   873  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 12:31:44.681   371   871 D CommandListener: Setting iface cfg
,08-11 12:31:44.683   873  1303 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,08-11 12:31:44.684   873  1303 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-11 12:31:44.741   873  1304 E native  : do suspend true
,08-11 12:31:44.756   873  1303 D WifiNative-HAL: p2pGetDeviceAddress
,08-11 12:31:44.758   873  1303 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,08-11 12:31:44.771   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 12:31:46.171   873  1304 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,08-11 12:31:46.298   873  1304 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=10.12 rxSuccessRate=8.12 delta 1000 -> 994
,08-11 12:31:46.300   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,08-11 12:31:46.300   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 12:31:46.320   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,08-11 12:31:46.377   873  1304 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,08-11 12:31:46.382  1452  1452 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-11 12:31:46.639  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-11 12:31:46.647  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-11 12:31:46.648  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:31:46.649  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cafb705 removed from the list
,08-11 12:31:46.649  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:31:46.649  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:46.650  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:46.664  4017  4415 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-11 12:31:46.664  4017  4415 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 12:31:46.816  1452  1452 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-11 12:31:46.860  1452  1452 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-11 12:31:46.860  1452  1452 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,08-11 12:31:46.867   873  1304 D WifiConfigStore: Retrieve network priorities after PNO.
,08-11 12:31:46.878   873  1304 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,08-11 12:31:46.878   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 12:31:46.878   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,08-11 12:31:46.902   873  1304 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-11 12:31:46.918   371   871 D CommandListener: Setting iface cfg
,08-11 12:31:46.919   873  1304 D WifiStateMachine: Start Dhcp Watchdog 3
,08-11 12:31:46.927   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,08-11 12:31:46.958   873  4418 D DhcpClient: Receive thread started
,08-11 12:31:47.043   873  1304 E native  : do suspend false
,08-11 12:31:47.062   873  2140 D DhcpClient: Broadcasting DHCPDISCOVER
,08-11 12:31:47.075   873  4418 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172773, domain null
,08-11 12:31:47.076   873  2140 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172773 seconds
,08-11 12:31:47.080   873  2140 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,08-11 12:31:47.092   873  4418 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,08-11 12:31:47.093   873  2140 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,08-11 12:31:47.098   371   871 D CommandListener: Setting iface cfg
,08-11 12:31:47.109   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,08-11 12:31:47.113   873  2140 D DhcpClient: Scheduling renewal in 86399s
,08-11 12:31:47.116   873  1304 E native  : do suspend true
,08-11 12:31:47.130   873  1304 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
08-11 12:31:47.131   873  1304 D WifiConfigStore: No blacklist allowed without epno enabled
08-11 12:31:47.131   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-11 12:31:47.136   873  1306 D ConnectivityService: Adding iface wlan0 to network 102
08-11 12:31:47.137   873  1304 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-11 12:31:47.176   873  1306 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-11 12:31:47.176   873  1306 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,08-11 12:31:47.179   873  1306 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-11 12:31:47.183   873  1306 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,08-11 12:31:47.187   873  1306 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,08-11 12:31:47.197   873  1306 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,08-11 12:31:47.202   873  1306 D ConnectivityService: scheduleUnvalidatedPrompt 102
,08-11 12:31:47.203   873  1306 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,08-11 12:31:47.203   873  1306 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
08-11 12:31:47.203   873  1304 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,08-11 12:31:47.203   873  1306 D ConnectivityService:    accepting network in place of null
,08-11 12:31:47.203   873  1304 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-11 12:31:47.204   873  1306 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
08-11 12:31:47.211   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=390430, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,08-11 12:31:47.237   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 12:31:47.278   873  4416 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.208.46,2a00:1450:4001:812::200e
,08-11 12:31:47.302   371   871 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,08-11 12:31:47.308   873  1306 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,08-11 12:31:47.309   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:31:47.317   873   890 D Tethering: MasterInitialState.processMessage what=3
,08-11 12:31:47.333   873  1306 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:47.337  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:31:47.339  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:47.344  4017  4017 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:31:47.346  4017  4017 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:31:47.348  1852  1852 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-11 12:31:47.355   873  4416 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 11 Aug 2016 10:31:47 GMT], X-Android-Received-Millis=[1470911507354], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1470911507325]}
,08-11 12:31:47.356   873  1306 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-11 12:31:47.356  1852  1852 D SystemUpdateService: onCreate
08-11 12:31:47.356   873  1306 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
08-11 12:31:47.357   873  1306 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-11 12:31:47.358   873  1306 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-11 12:31:47.363  1852  1852 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-11 12:31:47.384  1852  1852 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-11 12:31:47.390  1852  4428 I SystemUpdateService: active receiver: enabled
,08-11 12:31:47.395  1852  1852 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-11 12:31:47.396  1852  1852 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,08-11 12:31:47.398  4170  4170 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-11 12:31:47.404  1852  4430 I MDM     : [222] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,08-11 12:31:47.404  1852  4430 W BaseAppContext: Using Auth Proxy for data requests.
,08-11 12:31:47.405  1852  4430 V GoogleAuthProtoRequest: [222] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 12:31:47.406  4170  4170 D SprintDMHelper: simOperator: 
08-11 12:31:47.406  4170  4170 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-11 12:31:47.391  1852  2387 I iu.UploadsManager: num queued entries: 0
,08-11 12:31:47.421  1852  2387 I iu.UploadsManager: num updated entries: 0
,08-11 12:31:47.429  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:31:47.433  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:31:47.441  1852  4428 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,08-11 12:31:47.453  1852  2387 I iu.SyncManager: NEXT; no task
,08-11 12:31:47.459  1852  4428 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,08-11 12:31:47.459  1852  4428 I SystemUpdateService: now status is 0 (complete)
,08-11 12:31:47.459  1852  4428 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
08-11 12:31:47.459  1852  4428 I SystemUpdateService: file has been verified
,08-11 12:31:47.459  1852  4428 I SystemUpdateService: OTA package size = 12249756
,08-11 12:31:47.475  1852  4428 I SystemUpdateService: showing system update notification
,08-11 12:31:47.493  1852  1852 D SystemUpdateService: onDestroy
,08-11 12:31:47.495  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,08-11 12:31:47.495  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
08-11 12:31:47.495  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:31:47.495  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:31:47.527  1852  4430 E MDM     : [222] SitrepService.a: Error sending sitrep.
,08-11 12:31:47.545  4128  4433 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,08-11 12:31:48.308   873  1306 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 101] cleared because we found a replacement network
,08-11 12:31:49.671  4017  4440 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
,08-11 12:31:49.672  4017  4415 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-11 12:31:49.672  4017  4440 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 12:31:49.672  4017  4415 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
,08-11 12:31:49.675  4017  4415 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 12:31:49.676  4017  4440 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 12:31:49.677  4017  4415 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:31:49.678  4017  4440 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:31:49.679  4017  4415 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 12:31:49.683  4017  4442 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 460, name: OutgoingSocketThread/Sender)
,08-11 12:31:49.684  4017  4440 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 12:31:49.685  4017  4443 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 459, name: IncomingSocketThread/Sender)
,08-11 12:31:49.687  4017  4444 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 461, name: OutgoingSocketThread/Receiver)
,08-11 12:31:49.688  4017  4444 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 461, thread name: OutgoingSocketThread/Receiver)
08-11 12:31:49.688  4017  4444 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 12:31:49.688  4017  4444 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 461, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 12:31:49.689  4017  4445 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 462, name: IncomingSocketThread/Receiver)
,08-11 12:31:49.690  4017  4445 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 462, thread name: IncomingSocketThread/Receiver)
08-11 12:31:49.690  4017  4445 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-11 12:31:49.691  4017  4445 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 462, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-11 12:31:52.671  4017  4063 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-11 12:31:52.675  4017  4063 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-11 12:31:52.682  4017  4063 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@9d2d146 Bundle[{}]
,08-11 12:31:52.682  4017  4063 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 12:31:52.683  4017  4063 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-11 12:31:52.684  4017  4063 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-11 12:31:52.685  4017  4063 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-11 12:31:52.686  4017  4063 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-11 12:31:52.686  4017  4063 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-11 12:31:52.692  4017  4063 I System.out: Running OutgoingSocketThread
,08-11 12:31:52.695  4017  4447 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-11 12:31:52.696  4017  4447 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-11 12:31:55.210   873  1306 D ConnectivityService: handlePromptUnvalidated 102
,08-11 12:31:55.706  4017  4448 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-11 12:31:55.706  4017  4448 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-11 12:31:55.707  4017  4448 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 12:31:55.707  4017  4447 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
,08-11 12:31:55.708  4017  4447 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-11 12:31:55.708  4017  4448 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:31:55.708  4017  4447 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-11 12:31:55.710  4017  4448 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-11 12:31:55.714  4017  4450 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 471, name: IncomingSocketThread/Sender)
08-11 12:31:55.716  4017  4447 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-11 12:31:55.718  4017  4451 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 472, name: IncomingSocketThread/Receiver)
,08-11 12:31:55.719  4017  4451 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 472, thread name: IncomingSocketThread/Receiver)
08-11 12:31:55.719  4017  4451 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
,08-11 12:31:55.719  4017  4451 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 472, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-11 12:31:55.719  4017  4447 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-11 12:31:55.723  4017  4452 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 473, name: OutgoingSocketThread/Sender)
08-11 12:31:55.723  4017  4453 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 474, name: OutgoingSocketThread/Receiver)
08-11 12:31:55.724  4017  4453 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 474, thread name: OutgoingSocketThread/Receiver)
08-11 12:31:55.724  4017  4453 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-11 12:31:55.724  4017  4453 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 474, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-11 12:31:58.708  4017  4063 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 483)
,08-11 12:31:58.712  4017  4063 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-11 12:31:58.714  4017  4063 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 484)
,08-11 12:31:58.721  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 12:31:58.721  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372a35a added. We now have 3 listener(s)
,08-11 12:31:58.727  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-11 12:31:58.728  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-11 12:31:58.728  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:31:58.729  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-11 12:31:58.729  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@731298b added. We now have 4 listener(s)
08-11 12:31:58.729  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 12:31:58.730  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:31:58.737  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:58.749  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:31:58.756  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:31:58.757  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:31:58.758  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:31:58.758  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:31:58.759  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:31:58.759  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:31:58.760  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:58.760  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:31:58.760  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 12:31:58.761  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372a35a removed from the list
08-11 12:31:58.761  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:58.761  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@731298b removed from the list
,08-11 12:31:58.764  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:58.771  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:58.771  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:31:58.771  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:58.773  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:58.773  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:58.776  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:58.776  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:58.776  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:58.776  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@731298b not in the list
08-11 12:31:58.777  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:58.777  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:31:58.781  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:31:58.781  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:31:58.782  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:31:58.782  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@731298b not in the list
,08-11 12:31:58.782  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:31:58.783  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:31:58.783  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:31:58.783  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@372a35a not in the list
08-11 12:31:58.785  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-11 12:31:58.785  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f9be81 added. We now have 3 listener(s)
,08-11 12:31:58.792  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 12:31:58.792  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:31:58.793  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:31:58.793  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:31:58.794  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279b26 added. We now have 4 listener(s)
08-11 12:31:58.794  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:31:58.795  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:31:58.801  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:31:58.815  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:31:58.821  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:31:58.822  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 12:31:58.822  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-11 12:31:58.822  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-11 12:31:58.822  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-11 12:31:58.823  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:31:58.823  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-11 12:31:58.830  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:58.832  4017  4063 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-11 12:31:58.832  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-11 12:31:58.839  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:31:58.845  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:31:58.847  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 12:31:58.847  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 12:31:58.859  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-11 12:31:58.860  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-11 12:31:58.860  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-11 12:31:58.862  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:31:58.870  4362  4401 D BtGatt.GattService: registerClient() - UUID=ea1b1ee7-3394-45e5-a372-383be6899342
,08-11 12:31:58.873  4362  4378 D BtGatt.GattService: onClientRegistered() - UUID=ea1b1ee7-3394-45e5-a372-383be6899342, clientIf=5
,08-11 12:31:58.876  4017  4027 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-11 12:31:58.880  4362  4373 D BtGatt.GattService: start scan with filters
,08-11 12:31:58.891  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-11 12:31:58.892  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-11 12:31:58.892  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-11 12:31:58.892  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-11 12:31:58.892  4362  4381 D BtGatt.ScanManager: handling starting scan
,08-11 12:31:58.898  4362  4381 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@780b77a
,08-11 12:31:58.904  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 12:31:58.905  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-11 12:31:58.905  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-11 12:31:58.916  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 12:31:58.918  4362  4378 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-11 12:31:58.918  4362  4378 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:58.921  4362  4381 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-11 12:31:58.929  4017  4063 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-11 12:31:58.930  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:58.930  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-11 12:31:58.930  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:31:58.930  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 12:31:58.931  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 12:31:58.931  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,08-11 12:31:58.931  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 12:31:58.931  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 12:31:58.931  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 12:31:58.932  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-11 12:31:58.933  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:31:58.935  4362  4401 D BtGatt.GattService: stopScan() - queue size =1
,08-11 12:31:58.937  4362  4373 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 12:31:58.938  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:31:58.938  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-11 12:31:58.938  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-11 12:31:58.939  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-11 12:31:58.939  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-11 12:31:58.942  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:31:58.942  4362  4378 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
08-11 12:31:58.942  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 12:31:58.942  4362  4378 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:31:58.943  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 12:31:58.943  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-11 12:31:58.944  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:31:58.944  4362  4381 D BtGatt.ScanManager: Starting BLE batch scan
08-11 12:31:58.945  4362  4381 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-11 12:31:58.947  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:31:58.947  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-11 12:31:58.948  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-11 12:31:58.967  4362  4378 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-11 12:31:58.968  4362  4378 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:58.979  4362  4378 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-11 12:31:58.980  4362  4378 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:58.997  4362  4378 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,08-11 12:31:58.998  4362  4378 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:58.998  4362  4381 D BtGatt.ScanManager: stopping BLe Batch
,08-11 12:31:59.011  4362  4378 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-11 12:31:59.012  4362  4378 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-11 12:31:59.012  4362  4381 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-11 12:31:59.052  4362  4378 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,08-11 12:31:59.053  4362  4378 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-11 12:31:59.054  4362  4378 D BtGatt.GattService: current time is 402274232582
08-11 12:31:59.054  4362  4378 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -89, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 12:31:59.058  4362  4378 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
,08-11 12:31:59.450  4017  4017 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-11 12:31:59.450  4017  4017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:31:59.450  4017  4017 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 12:32:01.947  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:32:01.948  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-11 12:32:01.948  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-11 12:32:01.948  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-11 12:32:01.949  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:32:01.949  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-11 12:32:01.949  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-11 12:32:01.950  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f9be81 removed from the list
,08-11 12:32:01.950  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:32:01.951  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279b26 removed from the list
08-11 12:32:01.951  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
,08-11 12:32:01.951  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:32:01.953  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:32:01.953  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:32:01.958  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-11 12:32:01.958  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:32:01.959  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:32:01.959  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279b26 not in the list
08-11 12:32:01.959  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:32:01.960  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-11 12:32:01.963  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-11 12:32:01.963  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-11 12:32:01.963  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-11 12:32:01.964  4017  4063 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@279b26 not in the list
08-11 12:32:01.964  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:32:01.964  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:32:01.965  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:32:01.965  4017  4063 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f9be81 not in the list
08-11 12:32:01.967  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-11 12:32:01.967  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa33f03 added. We now have 3 listener(s)
,08-11 12:32:01.973  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 12:32:01.974  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:32:01.974  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:32:01.974  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-11 12:32:01.975  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@506ee80 added. We now have 4 listener(s)
08-11 12:32:01.975  4017  4063 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:32:01.976  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 12:32:01.983  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:32:01.993  4017  4063 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 12:32:01.998  4017  4063 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-11 12:32:01.999  4017  4063 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-11 12:32:01.999  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-11 12:32:02.001  4017  4063 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-11 12:32:02.001  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-11 12:32:02.004  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-11 12:32:02.004  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-11 12:32:02.005  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-11 12:32:02.005  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-11 12:32:02.005  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-11 12:32:02.008  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-11 12:32:02.008  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-11 12:32:02.009  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-11 12:32:02.009  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-11 12:32:02.009  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-11 12:32:02.009  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:32:02.009  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-11 12:32:02.012  4017  4454 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-11 12:32:02.014  4017  4017 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:32:02.014  4017  4017 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-11 12:32:02.019  4017  4063 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-11 12:32:02.020  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-11 12:32:02.021  4017  4454 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,08-11 12:32:02.026  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-11 12:32:02.027  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-11 12:32:02.028  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-11 12:32:02.031  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
,08-11 12:32:02.032  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-11 12:32:02.032  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 F8 CF C5 D9 E5 61
08-11 12:32:02.034  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 12:32:02.034  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, -8, -49, -59, -39, -27, 97]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
08-11 12:32:02.034  4017  4063 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting...
08-11 12:32:02.036  4017  4063 D BluetoothAdapter: STATE_ON
,08-11 12:32:02.040  4362  4373 D BtGatt.GattService: registerClient() - UUID=ccb53df4-5e14-4a64-833a-27f83f56ad8e
,08-11 12:32:02.041  4362  4378 D BtGatt.GattService: onClientRegistered() - UUID=ccb53df4-5e14-4a64-833a-27f83f56ad8e, clientIf=5
08-11 12:32:02.042  4017  4028 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,08-11 12:32:02.046  4362  4380 D BtGatt.AdvertiseManager: message : 0
,08-11 12:32:02.052  4362  4380 D BtGatt.AdvertiseManager: starting multi advertising
,08-11 12:32:02.088  4362  4378 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,08-11 12:32:02.113  4362  4378 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,08-11 12:32:02.115  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,08-11 12:32:02.116  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,08-11 12:32:02.123  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-11 12:32:02.127  4017  4017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,08-11 12:32:02.128  4017  4017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess
,08-11 12:32:02.129  4017  4017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
,08-11 12:32:02.129  4017  4017 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: true
08-11 12:32:02.130  4017  4017 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]
08-11 12:32:02.130  4017  4017 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING]
,08-11 12:32:02.142  4017  4017 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 12:32:02.142  4017  4017 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,08-11 12:32:02.644  4017  4017 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
08-11 12:32:02.645  4017  4017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,08-11 12:32:02.645  4017  4017 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-11 12:32:05.128  4017  4063 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-11 12:32:05.128  4017  4063 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
08-11 12:32:05.129  4017  4063 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-11 12:32:05.129  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,08-11 12:32:05.130  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-11 12:32:05.130  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-11 12:32:05.133  4017  4454 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-11 12:32:05.134  4017  4454 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,08-11 12:32:05.134  4017  4454 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-11 12:32:05.134  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
,08-11 12:32:05.134  4017  4063 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-11 12:32:05.135  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-11 12:32:05.135  4017  4017 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-11 12:32:05.135  4017  4017 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,08-11 12:32:05.135  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-11 12:32:05.136  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-11 12:32:05.136  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-11 12:32:05.137  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-11 12:32:05.139  4017  4063 D BluetoothAdapter: STATE_ON
08-11 12:32:05.139  4017  4063 D BluetoothLeScanner: could not find callback wrapper
08-11 12:32:05.140  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-11 12:32:05.140  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
08-11 12:32:05.143  4362  4380 D BtGatt.AdvertiseManager: message : 1
,08-11 12:32:05.145  4362  4380 D BtGatt.AdvertiseManager: stop advertise for client 5
08-11 12:32:05.152  4362  4378 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,08-11 12:32:05.152  4362  4378 D BtGatt.GattService: Client app is not null!
,08-11 12:32:05.164  4362  4372 D BtGatt.GattService: unregisterClient() - clientIf=5
,08-11 12:32:05.164  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-11 12:32:05.164  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
08-11 12:32:05.164  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: false
08-11 12:32:05.164  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]
,08-11 12:32:05.165  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED]
08-11 12:32:05.166  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-11 12:32:05.167  4017  4063 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-11 12:32:05.167  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-11 12:32:05.168  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-11 12:32:05.171  4017  4017 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-11 12:32:05.171  4017  4063 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-11 12:32:05.171  4017  4017 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-11 12:32:05.171  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-11 12:32:05.172  4017  4017 D AndroidRuntime: Shutting down VM
,08-11 12:32:05.172  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,--------- beginning of crash
08-11 12:32:05.173  4017  4017 E AndroidRuntime: FATAL EXCEPTION: main
08-11 12:32:05.173  4017  4017 E AndroidRuntime: Process: com.test.thalitest, PID: 4017
08-11 12:32:05.173  4017  4017 E AndroidRuntime: java.lang.NullPointerException: Attempt to invoke virtual method 'io.jxcore.node.JXcoreThaliCallback io.jxcore.node.StartStopOperation.getCallback()' on a null object reference
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at io.jxcore.node.StartStopOperationHandler.checkCurrentOperationStatus(StartStopOperationHandler.java:105)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at io.jxcore.node.ConnectionHelper.onConnectionManagerStateChanged(ConnectionHelper.java:360)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at org.thaliproject.p2p.btconnectorlib.ConnectionManager$4.run(ConnectionManager.java:447)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:32:05.173  4017  4017 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:32:05.172  4017  4063 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-11 12:32:05.173  4017  4063 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa33f03 removed from the list
,08-11 12:32:05.173  4017  4063 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-11 12:32:05.174  4017  4063 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@506ee80 removed from the list
08-11 12:32:05.174  4017  4063 D io.jxcore.node.ConnectivityMonitor: stop
08-11 12:32:05.174  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:32:05.176  4017  4063 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-11 12:32:05.178   873  1379 W ActivityManager:   Force finishing activity com.test.thalitest/.MainActivity
08-11 12:32:05.178  4017  4063 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-11 12:32:05.188  4017  4017 I Process : Sending signal. PID: 4017 SIG: 9
,08-11 12:32:05.264   873   884 I WindowState: WIN DEATH: Window{5afb5c1 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:32:05.265   873  1305 D WifiService: Client connection lost with reason: 4
08-11 12:32:05.265   873  1728 D GraphicsStats: Buffer count: 2
,08-11 12:32:05.286   873  1379 I ActivityManager: Process com.test.thalitest (pid 4017) has died
,08-11 12:32:05.347   873  1703 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 4017 uid 10000
,08-11 12:32:05.350  1650  1650 I Keyboard.Facilitator: onFinishInput()
,08-11 12:32:25.066   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=428285, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 12:33:05.392  1650  1752 I Keyboard.Facilitator.LanguageModelFlusher: run()
08-11 12:33:05.393  1650  1752 I Keyboard.Facilitator: flushDynamicLanguageModels()
,08-11 12:33:05.434  1492  1492 I ConfigService: onCreate
,08-11 12:33:10.505  1492  1492 I ConfigService: onDestroy
,08-11 12:33:29.525  3626  4462 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 12:33:29.554  3626  4463 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 12:33:29.575  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:33:29.578  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:33:29.626  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 12:33:29.626  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 12:33:29.626  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:33:29.627  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:33:29.668  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:33:29.673  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:33:29.722  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 12:33:29.722  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 12:33:29.722  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:33:29.722  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:33:29.754  3626  4463 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 12:33:29.755  3626  4462 E BooksSync: Soft error
08-11 12:33:29.755  3626  4462 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:33:29.755  3626  4462 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 12:33:29.756  3626  4462 E BooksSync: Sync error
08-11 12:33:29.756  3626  4462 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:33:29.756  3626  4462 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 12:33:29.756  3626  4462 I BooksSync: Finished books sync
,08-11 12:33:29.769   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 492636, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:33:47.567  1492  1983 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 12:34:01.660  3626  4466 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 12:34:01.694  3626  4467 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 12:34:01.710  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:01.714  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:01.754  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 12:34:01.754  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 12:34:01.754  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:34:01.754  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:34:01.795  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:01.799  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:01.842  1492  1880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 12:34:01.843  1492  1880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 12:34:01.843  1492  1880 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:34:01.843  1492  1880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:34:01.871  3626  4467 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 12:34:01.874  3626  4466 E BooksSync: Soft error
08-11 12:34:01.874  3626  4466 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:34:01.874  3626  4466 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 12:34:01.874  3626  4466 E BooksSync: Sync error
08-11 12:34:01.874  3626  4466 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:34:01.874  3626  4466 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 12:34:01.874  3626  4466 I BooksSync: Finished books sync
,08-11 12:34:01.888   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 524736, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:34:32.107  3162  4469 V KeepSync: Connecting to GoogleApiClient
,08-11 12:34:32.107   873  1386 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 12:34:32.166  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:32.169  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:32.216  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-11 12:34:32.216  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 12:34:32.216  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:34:32.216  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:34:32.245  1852  4470 V BaseAuthAsyncOperation: access token request failed
,08-11 12:34:32.246  3162  4469 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 12:34:32.314  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 12:34:32.315  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 12:34:32.315  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:34:32.315  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:34:32.339  3162  4469 E KeepSync: IOException
08-11 12:34:32.339  3162  4469 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 12:34:32.339  3162  4469 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:34:32.339  3162  4469 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 12:34:32.339  3162  4469 E KeepSync: 	... 10 more
,08-11 12:34:32.339  3162  4469 W KeepSync: Sync result 2
,08-11 12:34:32.351   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 526245, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:34:39.344  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:39.346  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:34:39.364  3899  4471 V GoogleAuthProtoRequest: [350] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 12:34:39.407  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-11 12:34:39.407  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
,08-11 12:34:39.407  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:34:39.408  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:34:39.430  3899  4471 W ExperimentUpdateService: [350] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: [350] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 12:34:39.431  3899  4471 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 12:35:02.785  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:35:02.788  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:35:02.840  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:35:02.840  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:35:02.840  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:35:02.841  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:35:02.857  3580  4474 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:35:02.857  3580  4474 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:35:02.857  3580  4474 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	... 12 more
08-11 12:35:02.857  3580  4474 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at fal.a(PG:38)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:35:02.857  3580  4474 E HttpOperation: 	... 14 more
,08-11 12:35:02.914  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:35:02.914  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:35:02.915  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:35:02.915  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:35:02.935  3580  4474 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:35:02.935  3580  4474 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at hec.a(PG:42)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at hee.a(PG:102)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at czr.a(PG:65)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at kka.a(PG:108)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:35:02.935  3580  4474 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	... 15 more
08-11 12:35:02.935  3580  4474 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at fal.a(PG:38)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:35:02.935  3580  4474 E HttpOperation: 	... 17 more
,08-11 12:35:02.935  3580  4474 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:35:02.935  3580  4474 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	... 15 more
08-11 12:35:02.935  3580  4474 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 12:35:02.935  3580  4474 E ExperimentLoader: 	... 17 more
,08-11 12:35:03.052   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 575365, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:35:03.095  3162  4476 V KeepSync: Connecting to GoogleApiClient
08-11 12:35:03.095   873  1703 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 12:35:03.192  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 12:35:03.192  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-11 12:35:03.192  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:35:03.192  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:35:03.208  1852  4477 V BaseAuthAsyncOperation: access token request failed
,08-11 12:35:03.209  3162  4476 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 12:35:03.258  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 12:35:03.258  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-11 12:35:03.258  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:35:03.258  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:35:03.274  3162  4476 E KeepSync: IOException
08-11 12:35:03.274  3162  4476 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 12:35:03.274  3162  4476 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:35:03.274  3162  4476 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 12:35:03.274  3162  4476 E KeepSync: 	... 10 more
08-11 12:35:03.274  3162  4476 W KeepSync: Sync result 2
,08-11 12:35:03.279   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 586168, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:35:04.553   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587772, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 12:35:33.853  3626  4480 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 12:35:33.879  3626  4481 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 12:35:33.889  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:35:33.892  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:35:33.918  1492  1880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 12:35:33.918  1492  1880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 12:35:33.918  1492  1880 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:35:33.918  1492  1880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:35:33.946  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:35:33.949  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:35:33.978  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 12:35:33.978  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 12:35:33.978  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:35:33.978  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:35:33.997  3626  4481 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 12:35:33.998  3626  4480 E BooksSync: Soft error
08-11 12:35:33.998  3626  4480 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:35:33.998  3626  4480 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 12:35:33.998  3626  4480 E BooksSync: Sync error
08-11 12:35:33.998  3626  4480 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:35:33.998  3626  4480 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 12:35:33.998  3626  4480 I BooksSync: Finished books sync
,08-11 12:35:34.014   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 588602, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:35:41.898   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=625117, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 12:35:52.514   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=635733, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 12:36:04.267  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:36:04.269  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:36:04.308  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:36:04.308  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:36:04.308  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth,
,08-11 12:36:04.308  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:36:04.337  3580  4488 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:36:04.337  3580  4488 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:36:04.337  3580  4488 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	... 12 more
08-11 12:36:04.337  3580  4488 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at fal.a(PG:38)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:36:04.337  3580  4488 E HttpOperation: 	... 14 more
,08-11 12:36:04.381  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:36:04.382  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:36:04.382  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:36:04.382  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:36:04.401  3580  4488 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:36:04.401  3580  4488 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at hec.a(PG:42)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at hee.a(PG:102)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at czr.a(PG:65)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at kka.a(PG:108)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	,at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:36:04.401  3580  4488 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:36:04.401  3580  4488 E HttpOperation: 	... 15 more
08-11 12:36:04.401  3580  4488 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:36:04.401  3580  4488 E HttpOperation: 	at fal.a(PG:38)
,08-11 12:36:04.401  3580  4488 E HttpOperation: 	at jdj.a(PG:4089),
08-11 12:36:04.401  3580  4488 E HttpOperation: 	... 17 more
,08-11 12:36:04.401  3580  4488 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:36:04.401  3580  4488 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	... 15 more
08-11 12:36:04.401  3580  4488 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 12:36:04.401  3580  4488 E ExperimentLoader: 	... 17 more
,08-11 12:36:04.514   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 619242, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:36:04.574  3162  4490 V KeepSync: Connecting to GoogleApiClient
,08-11 12:36:04.575   873  1379 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 12:36:04.669  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 12:36:04.669  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-11 12:36:04.669  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:36:04.669  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:36:04.700  1852  4491 V BaseAuthAsyncOperation: access token request failed
,08-11 12:36:04.701  3162  4490 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 12:36:04.767  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,08-11 12:36:04.767  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-11 12:36:04.767  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:36:04.767  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:36:04.797  3162  4490 E KeepSync: IOException
08-11 12:36:04.797  3162  4490 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 12:36:04.797  3162  4490 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:36:04.797  3162  4490 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 12:36:04.797  3162  4490 E KeepSync: 	... 10 more
,08-11 12:36:04.798  3162  4490 W KeepSync: Sync result 2
,08-11 12:36:04.803   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 647693, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:36:30.219   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=673439, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 12:36:52.364   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=695584, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 12:37:10.640  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:37:10.643  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:37:10.707  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:37:10.707  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 12:37:10.708  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:37:10.708  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:37:10.745  3580  4496 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:37:10.745  3580  4496 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:37:10.745  3580  4496 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	... 12 more
08-11 12:37:10.745  3580  4496 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at fal.a(PG:38)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:37:10.745  3580  4496 E HttpOperation: 	... 14 more
,08-11 12:37:10.830  1492  1880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:37:10.831  1492  1880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:37:10.831  1492  1880 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:37:10.831  1492  1880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:37:10.857  3580  4496 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:37:10.857  3580  4496 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at hec.a(PG:42)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at hee.a(PG:102)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at czr.a(PG:65)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at kka.a(PG:108)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:37:10.857  3580  4496 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	... 15 more
08-11 12:37:10.857  3580  4496 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at fal.a(PG:38)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:37:10.857  3580  4496 E HttpOperation: 	... 17 more
,08-11 12:37:10.857  3580  4496 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:37:10.857  3580  4496 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	... 15 more
08-11 12:37:10.857  3580  4496 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 12:37:10.857  3580  4496 E ExperimentLoader: 	... 17 more
,08-11 12:37:11.000   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 713674, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:37:29.739   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=732959, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 12:37:41.119  3626  4500 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 12:37:41.163  3626  4501 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 12:37:41.179  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:37:41.184  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:37:41.217  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 12:37:41.217  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 12:37:41.217  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:37:41.217  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:37:41.253  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:37:41.258  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:37:41.298  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 12:37:41.298  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 12:37:41.298  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:37:41.298  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:37:41.330  3626  4501 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 12:37:41.331  3626  4500 E BooksSync: Soft error
08-11 12:37:41.331  3626  4500 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:37:41.331  3626  4500 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 12:37:41.331  3626  4500 E BooksSync: Sync error
08-11 12:37:41.331  3626  4500 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:37:41.331  3626  4500 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 12:37:41.331  3626  4500 I BooksSync: Finished books sync
,08-11 12:37:41.346   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 744223, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:37:50.751   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=753970, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-11 12:38:11.745  3162  4505 V KeepSync: Connecting to GoogleApiClient
,08-11 12:38:11.746   873  1728 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 12:38:11.832  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:38:11.836  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:38:11.861  1492  1880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 12:38:11.861  1492  1880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 12:38:11.861  1492  1880 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:38:11.861  1492  1880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:38:11.883  1852  4506 V BaseAuthAsyncOperation: access token request failed
,08-11 12:38:11.884  3162  4505 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 12:38:11.944  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 12:38:11.944  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-11 12:38:11.945  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:38:11.945  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:38:11.962  3162  4505 E KeepSync: IOException
08-11 12:38:11.962  3162  4505 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 12:38:11.962  3162  4505 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:38:11.962  3162  4505 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 12:38:11.962  3162  4505 E KeepSync: 	... 10 more
08-11 12:38:11.962  3162  4505 W KeepSync: Sync result 2
,08-11 12:38:11.975   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 770411, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:38:28.084   873  4417 D NetlinkSocketObserver: NeighborEvent{elapsedMs=791304, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-11 12:39:23.241  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:39:23.243  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:39:23.273  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-11 12:39:23.273  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 12:39:23.273  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:39:23.274  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:39:23.290  3580  4511 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:39:23.290  3580  4511 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:39:23.290  3580  4511 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:39:23.290  3580  4511 E HttpOperation: 	,at jdj.a(PG:4091)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	... 12 more
08-11 12:39:23.290  3580  4511 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at fal.a(PG:38)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:39:23.290  3580  4511 E HttpOperation: 	... 14 more
,08-11 12:39:23.334  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-11 12:39:23.334  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 12:39:23.334  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:39:23.334  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:39:23.360  3580  4511 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:39:23.360  3580  4511 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at hec.a(PG:42)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at hee.a(PG:102)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at czr.a(PG:65)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at kka.a(PG:108)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:39:23.360  3580  4511 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	... 15 more
08-11 12:39:23.360  3580  4511 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at fal.a(PG:38)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:39:23.360  3580  4511 E HttpOperation: 	... 17 more
08-11 12:39:23.361  3580  4511 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:39:23.361  3580  4511 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jdj.a(PG:1,125)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	... 15 more
08-11 12:39:23.361  3580  4511 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 12:39:23.361  3580  4511 E ExperimentLoader: 	... 17 more
,08-11 12:39:23.497   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 846101, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:39:41.368  1492  1983 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 12:41:31.290  1852  4519 I EventLogService: Opted in for usage reporting
08-11 12:41:31.290  1852  4519 I EventLogService: Aggregate from 1470910203728 (log), 1470910203728 (data)
,08-11 12:41:31.324  1852  4519 W EventLogAggregator: Unknown tag: snet_gcore
08-11 12:41:31.324  1852  4519 W EventLogAggregator: Unknown tag: snet_launch_service
,08-11 12:41:31.399  1852  4519 I ServiceDumpSys: dumping service [account]
,08-11 12:41:55.365  3626  4523 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 12:41:55.396  3626  4524 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 12:41:55.408  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:41:55.410  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:41:55.443  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 12:41:55.444  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 12:41:55.444  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:41:55.444  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:41:55.475  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:41:55.477  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:41:55.511  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-11 12:41:55.511  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,08-11 12:41:55.511  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:41:55.511  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:41:55.531  3626  4524 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 12:41:55.532  3626  4523 E BooksSync: Soft error
08-11 12:41:55.532  3626  4523 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:41:55.532  3626  4523 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-11 12:41:55.533  3626  4523 E BooksSync: Sync error
08-11 12:41:55.533  3626  4523 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:41:55.533  3626  4523 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 12:41:55.533  3626  4523 I BooksSync: Finished books sync
,08-11 12:41:55.545   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 998542, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:42:25.875  3162  4526 V KeepSync: Connecting to GoogleApiClient
08-11 12:42:25.876   873  1386 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 12:42:25.929  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:42:25.932  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:42:25.971  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
08-11 12:42:25.972  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
08-11 12:42:25.972  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:42:25.972  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:42:25.997  1852  4527 V BaseAuthAsyncOperation: access token request failed
08-11 12:42:25.999  3162  4526 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 12:42:26.069  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 12:42:26.069  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
08-11 12:42:26.069  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:42:26.070  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:42:26.096  3162  4526 E KeepSync: IOException
08-11 12:42:26.096  3162  4526 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 12:42:26.096  3162  4526 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:42:26.096  3162  4526 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 12:42:26.096  3162  4526 E KeepSync: 	... 10 more
,08-11 12:42:26.096  3162  4526 W KeepSync: Sync result 2
,08-11 12:42:26.128   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1019972, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:42:39.547  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:42:39.550  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:42:39.566  3899  4530 V GoogleAuthProtoRequest: [351] a.<init>: mAccountName set to: thalitester@gmail.com
,08-11 12:42:39.608  1492  1880 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-11 12:42:39.609  1492  1880 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-11 12:42:39.609  1492  1880 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:42:39.609  1492  1880 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: [351] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: [351] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-11 12:42:39.632  3899  4530 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,08-11 12:43:47.775  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:43:47.777  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:43:47.898  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:43:47.898  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:43:47.898  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:43:47.898  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:43:47.935  3580  4534 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:43:47.935  3580  4534 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:43:47.935  3580  4534 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	... 12 more
08-11 12:43:47.935  3580  4534 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at fal.a(PG:38)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:43:47.935  3580  4534 E HttpOperation: 	... 14 more
,08-11 12:43:48.018  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:43:48.018  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
08-11 12:43:48.018  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:43:48.018  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:43:48.038  3580  4534 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:43:48.038  3580  4534 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at hec.a(PG:42)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at hee.a(PG:102)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at czr.a(PG:65)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at kka.a(PG:108)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:43:48.038  3580  4534 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	... 15 more
08-11 12:43:48.038  3580  4534 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at fal.a(PG:38)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:43:48.038  3580  4534 E HttpOperation: 	... 17 more
,08-11 12:43:48.039  3580  4534 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:43:48.039  3580  4534 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	... 15 more
08-11 12:43:48.039  3580  4534 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	at jdj.a(PG:4089)
08-11 12:43:48.039  3580  4534 E ExperimentLoader: 	... 17 more
,08-11 12:43:48.183   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1110477, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:44:26.136  1492  1983 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 12:45:34.932   873   885 I UsageStatsService: User[0] Flushing usage stats to disk
,08-11 12:50:23.669  3626  4554 I BooksSync: Starting books sync for 61035162, extras: ade
,08-11 12:50:23.691  3626  4555 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-11 12:50:23.711  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:50:23.713  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:50:23.761  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 12:50:23.761  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 12:50:23.762  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:50:23.762  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:50:23.797  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-11 12:50:23.798  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:50:23.821  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
08-11 12:50:23.821  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-11 12:50:23.821  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:50:23.821  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:50:23.846  3626  4555 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-11 12:50:23.846  3626  4554 E BooksSync: Soft error
08-11 12:50:23.846  3626  4554 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:50:23.846  3626  4554 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 12:50:23.847  3626  4554 E BooksSync: Sync error
08-11 12:50:23.847  3626  4554 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-11 12:50:23.847  3626  4554 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-11 12:50:23.847  3626  4554 I BooksSync: Finished books sync
,08-11 12:50:23.854   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1506717, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:50:54.031  3162  4557 V KeepSync: Connecting to GoogleApiClient
,08-11 12:50:54.032   873  1732 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,08-11 12:50:54.079  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:50:54.081  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:50:54.105  1492  2010 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,08-11 12:50:54.105  1492  2010 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
,08-11 12:50:54.105  1492  2010 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:50:54.105  1492  2010 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:50:54.122  1852  4558 V BaseAuthAsyncOperation: access token request failed
,08-11 12:50:54.123  3162  4557 V KeepSync: GoogleApiClient failed to connect with error code: 4
,08-11 12:50:54.165  1492  1504 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
08-11 12:50:54.166  1492  1504 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,08-11 12:50:54.166  1492  1504 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:50:54.166  1492  1504 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:50:54.182  3162  4557 E KeepSync: IOException
08-11 12:50:54.182  3162  4557 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
08-11 12:50:54.182  3162  4557 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
08-11 12:50:54.182  3162  4557 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
08-11 12:50:54.182  3162  4557 E KeepSync: 	... 10 more
,08-11 12:50:54.182  3162  4557 W KeepSync: Sync result 2
,08-11 12:50:54.188   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, POLL, currentRunTime 1518901, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-11 12:52:36.058  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:52:36.060  1492  1492 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-11 12:52:36.095  1492  2049 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,08-11 12:52:36.095  1492  2049 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:52:36.095  1492  2049 I GLSUser : [GLSUser] Extracting token using key: Auth
,08-11 12:52:36.095  1492  2049 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:52:36.116  3580  4564 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
08-11 12:52:36.116  3580  4564 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at blb.a(PG:3937)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at czp.a(PG:18188)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:52:36.116  3580  4564 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	... 12 more
08-11 12:52:36.116  3580  4564 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at fal.a(PG:38)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:52:36.116  3580  4564 E HttpOperation: 	... 14 more
,08-11 12:52:36.186  1492  1503 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
08-11 12:52:36.186  1492  1503 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,08-11 12:52:36.186  1492  1503 I GLSUser : [GLSUser] Extracting token using key: Auth
08-11 12:52:36.186  1492  1503 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-11 12:52:36.204  3580  4564 E HttpOperation: [getmobileexperiments] Unexpected exception
08-11 12:52:36.204  3580  4564 E HttpOperation: java.io.IOException: Cannot obtain authentication token
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jdm.a(PG:82)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jcs.o(PG:406)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jcn.a(PG:1379)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jcs.i(PG:143)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at hec.a(PG:42)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at hee.a(PG:102)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at czr.a(PG:65)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at kka.a(PG:108)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at czp.a(PG:19176)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at czp.a(PG:9081)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at czq.run(PG:1686)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:52:36.204  3580  4564 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jdj.a(PG:4091)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jdj.a(PG:1125)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jdm.a(PG:77)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	... 15 more
08-11 12:52:36.204  3580  4564 E HttpOperation: Caused by: faj: BadAuthentication
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at fal.a(PG:38)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	at jdj.a(PG:4089)
08-11 12:52:36.204  3580  4564 E HttpOperation: 	... 17 more
,08-11 12:52:36.204  3580  4564 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
08-11 12:52:36.204  3580  4564 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jdm.a(PG:82)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jcs.o(PG:406)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jcn.a(PG:1379)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jcs.i(PG:143)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at hec.a(PG:42)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at hee.a(PG:102)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at czr.a(PG:65)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at kka.a(PG:108)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at czp.a(PG:19176)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at czp.a(PG:9081)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at czq.run(PG:1686)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jdj.a(PG:4091)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jdj.a(PG:1125)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jdm.a(PG:77)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	... 15 more
08-11 12:52:36.204  3580  4564 E ExperimentLoader: Caused by: faj: BadAuthentication
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at fal.a(PG:38)
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	at jdj.a(PG:4089),
08-11 12:52:36.204  3580  4564 E ExperimentLoader: 	... 17 more,
,08-11 12:52:36.361   873   885 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1638923, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,TIME-OUT KILL (timeout was 1400000ms),08-11 12:54:02.791  4571  4571 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-11 12:54:02.796  4571  4571 D AndroidRuntime: CheckJNI is OFF
08-11 12:54:02.831  4571  4571 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-11 12:54:02.871  4571  4571 I Radio-JNI: register_android_hardware_Radio DONE
08-11 12:54:02.892  4571  4571 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-11 12:54:02.904   873   886 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-11 12:54:03.019   873   896 W PackageSettings: Skipping PackageSetting{294b89f com.example.hello/10273} due to missing metadata
08-11 12:54:03.069   873   896 I art     : Starting a blocking GC Explicit
08-11 12:54:03.123   873   896 I art     : Explicit concurrent mark sweep GC freed 34948(2MB) AllocSpace objects, 6(120KB) LOS objects, 33% free, 28MB/43MB, paused 651us total 53.340ms
08-11 12:54:03.144   873   896 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
08-11 12:54:03.152  4571  4571 I art     : System.exit called, status: 0
08-11 12:54:03.153  4571  4571 I AndroidRuntime: VM exiting with result code 0.
08-11 12:54:03.170   873   896 I ActivityManager: Start proc 4582:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
08-11 12:54:03.171   873   896 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
08-11 12:54:03.191  4362  4362 D BluetoothMapAppObserver: onReceive
08-11 12:54:03.192  4362  4362 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-11 12:54:03.202  1650  1650 I Keyboard.Facilitator: resetDictionaries() : en_US
08-11 12:54:03.205   873  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 12:54:03.206  1821  2021 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 12:54:03.207  3785  3785 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
08-11 12:54:03.210  1650  4592 I Keyboard.Facilitator.DecoderInitializer: run()
08-11 12:54:03.230  1650  4592 I Decoder : createOrResetDecoder
08-11 12:54:03.265  1708  1708 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
08-11 12:54:03.273   873  1703 I ActivityManager: Start proc 4597:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
08-11 12:54:03.305  1492  1492 I ConfigService: onCreate
08-11 12:54:03.316   873   873 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 12:54:03.318  4597  4597 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 12:54:03.322  1492  4610 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
08-11 12:54:03.325  1492  4610 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
08-11 12:54:03.327  1492  4610 W SQLiteOpenHelper: Opened config.db in read-only mode
08-11 12:54:03.336  1734  1832 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-11 12:54:03.336   873   885 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-11 12:54:03.337   873   885 E PackageManager: Failed to write settings, restoring backup
08-11 12:54:03.337   873   885 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-11 12:54:03.337   873   885 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-11 12:54:03.337   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-11 12:54:03.337   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-11 12:54:03.337   873   885 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-11 12:54:03.337   873   885 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.337   873   885 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.337   873   885 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:54:03.341   873   886 E DropBoxManagerService: Can't write: system_server_wtf
08-11 12:54:03.341   873   886 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-11 12:54:03.341   873   886 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:54:03.341   873   886 E DropBoxManagerService: 	... 13 more
08-11 12:54:03.350   873  1731 I ActivityManager: Start proc 4611:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-11 12:54:03.351  1734  1832 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-11 12:54:03.351  1734  1832 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1734
08-11 12:54:03.351  1734  1832 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.351  1734  1832 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:54:03.353   873  1728 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 12:54:03.356   873  4621 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:54:03.356   873  4621 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:54:03.356   873  4621 E DropBoxManagerService: 	... 5 more
08-11 12:54:03.358  1734  1832 I Process : Sending signal. PID: 1734 SIG: 9
08-11 12:54:03.364  1650  4592 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-11 12:54:03.394  1650  4592 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-11 12:54:03.395  1650  4592 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-11 12:54:03.396  1650  4592 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
08-11 12:54:03.399  1650  4592 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-11 12:54:03.399  1650  4592 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-11 12:54:03.399  1650  4592 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-11 12:54:03.399  1650  4592 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-11 12:54:03.400  1650  4592 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-11 12:54:03.400  1650  4592 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-11 12:54:03.400  1650  4592 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-11 12:54:03.400  1650  4592 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-11 12:54:03.400  1650  4592 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-11 12:54:03.400  1650  4592 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-11 12:54:03.433  4597  4597 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
08-11 12:54:03.441   279   279 E lowmemorykiller: Error writing /proc/1734/oom_score_adj; errno=22
08-11 12:54:03.454   873  1728 D GraphicsStats: Buffer count: 1
08-11 12:54:03.454   873  1730 I WindowState: WIN DEATH: Window{8c2d20d u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-11 12:54:03.464  4597  4631 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.469  4597  4627 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.469  4597  4627 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:54:03.490   873  1703 I ActivityManager: Start proc 4633:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
08-11 12:54:03.491   279   279 E lowmemorykiller: Error opening /proc/1734/oom_score_adj; errno=2
08-11 12:54:03.493   873  1728 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1734) has died
08-11 12:54:03.494   873  1728 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-11 12:54:03.496   873  1728 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
08-11 12:54:03.511   873   886 I ActivityManager: Start proc 4646:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-11 12:54:03.527  1852  4643 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
08-11 12:54:03.528  1852  4643 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
08-11 12:54:03.531  4633  4633 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
08-11 12:54:03.539  4597  4627 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
08-11 12:54:03.552  1492  1492 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-11 12:54:03.553  1492  1492 D AndroidRuntime: Shutting down VM
08-11 12:54:03.555  1492  1492 E AndroidRuntime: FATAL EXCEPTION: main
08-11 12:54:03.555  1492  1492 E AndroidRuntime: Process: com.google.process.gapps, PID: 1492
08-11 12:54:03.555  1492  1492 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-11 12:54:03.555  1492  1492 E AndroidRuntime: 	... 8 more
08-11 12:54:03.559   873  4661 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:54:03.559   873  4661 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:54:03.559   873  4661 E DropBoxManagerService: 	... 5 more
08-11 12:54:03.560  1492  1492 I Process : Sending signal. PID: 1492 SIG: 9
08-11 12:54:03.570   873  1731 I ActivityManager: Killing 4075:com.android.settings/1000 (adj 15): empty #17
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:54:03.571  4646  4646 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:54:03.571  4646  4646 D AndroidRuntime: Shutting down VM
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.589  4597  4631 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-11 12:54:03.589  4597  4631 E AndroidRuntime: Process: android.process.acore, PID: 4597
08-11 12:54:03.589  4597  4631 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.589  4597  4631 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-11 12:54:03.590  4597  4627 I Process : Sending signal. PID: 4597 SIG: 9
08-11 12:54:03.630   873  1305 D WifiService: Client connection lost with reason: 4
08-11 12:54:03.635   873  4664 E DropBoxManagerService: Can't write: system_app_crash
08-11 12:54:03.635   873  4664 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-11 12:54:03.635   873  4664 E DropBoxManagerService: 	... 5 more
08-11 12:54:03.642   873  1730 I ActivityManager: Process com.google.process.gapps (pid 1492) has died
08-11 12:54:03.642   873  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 1000ms
08-11 12:54:03.642   873  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 11000ms
08-11 12:54:03.642   873  1730 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
08-11 12:54:03.646  4646  4646 E AndroidRuntime: FATAL EXCEPTION: main
08-11 12:54:03.646  4646  4646 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4646
08-11 12:54:03.646  4646  4646 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-11 12:54:03.646  4646  4646 E AndroidRuntime: 	... 10 more

```
