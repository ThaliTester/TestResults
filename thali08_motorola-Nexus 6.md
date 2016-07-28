#### Test 77622416c9749bc_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main,
07-28 12:06:51.370   872  1993 D NetlinkSocketObserver: NeighborEvent{elapsedMs=268104, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
07-28 12:06:52.071  3691  3691 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-28 12:06:52.076  3691  3691 D AndroidRuntime: CheckJNI is OFF
07-28 12:06:52.118  3691  3691 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-28 12:06:52.163  3691  3691 I Radio-JNI: register_android_hardware_Radio DONE
07-28 12:06:52.183  3691  3691 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-28 12:06:52.190   872   882 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:06:52.255   872   882 I ActivityManager: Start proc 3701:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-28 12:06:52.263  3691  3691 D AndroidRuntime: Shutting down VM
07-28 12:06:52.401  3701  3701 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-28 12:06:52.427  3701  3701 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-28 12:06:52.433  3701  3701 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9165-9167)
07-28 12:06:52.433  3701  3701 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:06:52.447  3701  3701 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8927c97}
07-28 12:06:52.448  3701  3701 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:06:52.448  3701  3701 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-28 12:06:52.453  3701  3701 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-28 12:06:52.455  3701  3701 E SysUtils: ApplicationContext is null in ApplicationStatus
07-28 12:06:52.467  3701  3701 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-28 12:06:52.476  3701  3701 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 12:06:52.476  3701  3701 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-28 12:06:52.476  3701  3701 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-28 12:06:52.476  3701  3701 I Adreno  : Build Date                       : 10/20/15
07-28 12:06:52.476  3701  3701 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-28 12:06:52.476  3701  3701 I Adreno  : Local Branch                     : M14
07-28 12:06:52.476  3701  3701 I Adreno  : Remote Branch                    : 
07-28 12:06:52.476  3701  3701 I Adreno  : Remote Branch                    : 
07-28 12:06:52.476  3701  3701 I Adreno  : Reconstruct Branch               : 
,07-28 12:06:52.540   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@76e8bc9:true
07-28 12:06:52.593  3701  3701 W AwContents: onDetachedFromWindow called when already detached. Ignoring
07-28 12:06:52.610  3701  3701 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
07-28 12:06:52.670  3701  3738 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
07-28 12:06:52.693  3701  3725 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
07-28 12:06:52.740  3701  3738 I OpenGLRenderer: Initialized EGL, version 1.4
07-28 12:06:52.817   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +474ms (total +585ms)
07-28 12:06:52.826  1666  1666 I Keyboard.Facilitator: onFinishInput()
07-28 12:06:52.888  3701  3701 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3701
07-28 12:06:53.098  3701  3701 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
07-28 12:06:53.252  3701  3740 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680934608
07-28 12:06:53.261  3701  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:06:53.261  3701  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:06:53.261  3701  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:06:53.261  3701  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:06:53.261  3701  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
07-28 12:06:53.262  3701  3740 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@62e9aba added. We now have 1 listener(s)
07-28 12:06:53.276  3701  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
07-28 12:06:53.277  3701  3740 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:06:53.278  3701  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:06:53.279  3701  3740 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:06:53.284  3701  3740 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c6a2561 added. We now have 1 listener(s)
07-28 12:06:53.285  3701  3740 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:06:53.290   872  1316 D WifiService: New client listening to asynchronous messages
07-28 12:06:53.292  3701  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:06:53.292  3701  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-28 12:06:53.292  3701  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-28 12:06:53.292  3701  3740 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
07-28 12:06:53.299  3701  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:06:53.300  3701  3740 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
07-28 12:06:53.309  3701  3740 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:06:53.310  3701  3740 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:06:53.310  3701  3740 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 12:06:53.310  3701  3740 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:06:53.311  3701  3740 I io.jxcore.node.LifeCycleMonitor: start: OK
07-28 12:06:53.314  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:06:53.317  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:06:53.347  3701  3701 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
07-28 12:06:53.854  3701  3710 I art     : Background sticky concurrent mark sweep GC freed 69167(6MB) AllocSpace objects, 17(1584KB) LOS objects, 29% free, 23MB/32MB, paused 650us total 160.606ms
,07-28 12:06:54.526  3701  3748 W jxcore-log: Initializing JXcore engine
,07-28 12:06:54.526  3701  3748 W jxcore-log: JXcore engine is ready
,07-28 12:06:54.587  3748  3748 W Thread-322: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8803 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-28 12:06:54.587  3748  3748 W Thread-322: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[9516]" dev="sockfs" ino=9516 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-28 12:06:54.587  3748  3748 W Thread-322: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-28 12:06:54.587  3748  3748 W Thread-322: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28114]" dev="sockfs" ino=28114 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-28 12:06:54.602  3701  3748 W jxcore-log: Starting JXcore engine
,07-28 12:06:54.684  3701  3748 W jxcore-log: Platform android
07-28 12:06:54.684  3701  3748 W jxcore-log: 
,07-28 12:06:54.684  3701  3748 W jxcore-log: Process ARCH arm
07-28 12:06:54.684  3701  3748 W jxcore-log: 
,07-28 12:06:54.853  3701  3748 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:06:54.853  3701  3748 I jxcore-log: 
07-28 12:06:54.854  3701  3748 W jxcore-log: JXcore engine is started
,07-28 12:06:54.860  3701  3740 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-28 12:06:54.864  3701  3701 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 12:07:04.058  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:07:04.060  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:07:04.085  1527  1545 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-28 12:07:04.086  1527  1545 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-28 12:07:04.086  1527  1545 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-28 12:07:04.086  1527  1545 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:07:04.099  3442  3751 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-28 12:07:04.099  3442  3751 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jdm.a(PG:82)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jcs.o(PG:406)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jcn.a(PG:1379)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jcs.i(PG:143)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at blb.a(PG:3937)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at czp.a(PG:18188)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at czp.a(PG:9081)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at czq.run(PG:1686)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-28 12:07:04.099  3442  3751 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jdj.a(PG:4091)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jdj.a(PG:1125)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jdm.a(PG:77)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	... 12 more
07-28 12:07:04.099  3442  3751 E HttpOperation: Caused by: faj: BadAuthentication
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at fal.a(PG:38)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	at jdj.a(PG:4089)
07-28 12:07:04.099  3442  3751 E HttpOperation: 	... 14 more
,07-28 12:07:04.177  1527  1994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-28 12:07:04.177  1527  1994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-28 12:07:04.177  1527  1994 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-28 12:07:04.177  1527  1994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:07:04.191  3442  3751 E HttpOperation: [getmobileexperiments] Unexpected exception
07-28 12:07:04.191  3442  3751 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jdm.a(PG:82)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jcs.o(PG:406)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jcn.a(PG:1379)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jcs.i(PG:143)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at hec.a(PG:42)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at hee.a(PG:102)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at czr.a(PG:65)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at kka.a(PG:108)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at czp.a(PG:19176)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at czp.a(PG:9081)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at czq.run(PG:1686)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-28 12:07:04.191  3442  3751 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jdj.a(PG:4091)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jdj.a(PG:1125)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jdm.a(PG:77)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	... 15 more
07-28 12:07:04.191  3442  3751 E HttpOperation: Caused by: faj: BadAuthentication
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at fal.a(PG:38)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	at jdj.a(PG:4089)
07-28 12:07:04.191  3442  3751 E HttpOperation: 	... 17 more
,07-28 12:07:04.191  3442  3751 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-28 12:07:04.191  3442  3751 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jdm.a(PG:82)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jcs.o(PG:406)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jcn.a(PG:1379)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jcs.i(PG:143)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at hec.a(PG:42)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at hee.a(PG:102)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at czr.a(PG:65)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at kka.a(PG:108)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at czp.a(PG:19176)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at czp.a(PG:9081)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at czq.run(PG:1686)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jdj.a(PG:4091)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jdj.a(PG:1125)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jdm.a(PG:77)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	... 15 more
07-28 12:07:04.191  3442  3751 E ExperimentLoader: Caused by: faj: BadAuthentication
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at fal.a(PG:38)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	at jdj.a(PG:4089)
07-28 12:07:04.191  3442  3751 E ExperimentLoader: 	... 17 more
,07-28 12:07:04.273   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 280610, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-28 12:07:05.135  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:07:05.135  3701  3748 I jxcore-log: 
,07-28 12:07:05.138  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:07:05.138  3701  3748 I jxcore-log: 
,07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:05.152  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:07:05.157  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:07:05.160  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:07:05.160  3701  3748 I jxcore-log: 
,07-28 12:07:05.161  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:07:05.161  3701  3748 I jxcore-log: 
,07-28 12:07:05.506  3701  3748 D ExecuteNativeTests: Running unit tests
,07-28 12:07:05.564  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:07:05.564  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 added. We now have 2 listener(s)
07-28 12:07:05.565  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:07:05.565  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:05.566  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:05.566  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:05.566  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d added. We now have 2 listener(s)
07-28 12:07:05.566  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:05.566  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:07:05.572  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:05.589  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:07:05.592  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.593  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:07:05.595  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:07:05.597  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:07:05.597  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 12:07:05.598  3701  3748 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-28 12:07:05.598  3701  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:07:05.599  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:07:05.599  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1,
,07-28 12:07:05.599  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:07:05.599  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.599  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.600  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:07:05.600  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.600  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.600  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.600  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:07:05.600  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:05.600  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 removed from the list
07-28 12:07:05.600  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.600  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d removed from the list
07-28 12:07:05.606  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.607  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.607  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.607  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.607  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.608  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:05.608  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.608  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.609  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.610  3701  3748 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 12:07:05.611  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:07:05.611  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.611  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.611  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.611  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.611  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.611  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.611  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.611  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.611  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.611  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.611  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.611  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.611  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.619  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:05.619  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.619  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.619  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.623  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:07:05.624  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:07:05.625  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-28 12:07:05.625  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.625  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.625  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.625  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.625  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.625  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.626  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.626  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.626  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.626  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.626  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.626  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.626  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.626  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.627  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.627  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.628  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.628  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.628  3701  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:07:05.629  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:05.634  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:07:05.637  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:07:05.637  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:07:05.637  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:07:05.637  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:07:05.638  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:05.638  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:07:05.639  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:05.642  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:05.645  3701  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:07:05.646  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:07:05.659  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:07:05.664  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-28 12:07:05.665  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:07:05.671  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,07-28 12:07:05.676  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,07-28 12:07:05.677  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:07:05.677  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-28 12:07:05.679  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-28 12:07:05.681  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:05.690  2557  2771 D BtGatt.GattService: registerClient() - UUID=cd329343-2ab6-41c8-b4fb-674974a1bd1a
,07-28 12:07:05.691  2557  2617 D BtGatt.GattService: onClientRegistered() - UUID=cd329343-2ab6-41c8-b4fb-674974a1bd1a, clientIf=5
,07-28 12:07:05.693  3701  3712 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-28 12:07:05.696  2557  2763 D BtGatt.GattService: start scan with filters
,07-28 12:07:05.702  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:07:05.702  2557  2634 D BtGatt.ScanManager: handling starting scan
,07-28 12:07:05.705  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-28 12:07:05.706  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-28 12:07:05.706  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-28 12:07:05.706  2557  2634 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:05.714  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:07:05.716  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:07:05.717  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-28 12:07:05.718  2557  2617 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 12:07:05.718  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.719  2557  2634 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 12:07:05.724  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 12:07:05.737  3701  3748 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:07:05.737  3701  3701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:07:05.737  3701  3701 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-28 12:07:05.737  2557  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:07:05.738  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.739  2557  2634 D BtGatt.ScanManager: Starting BLE batch scan
,07-28 12:07:05.739  2557  2634 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-28 12:07:05.740  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.740  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:07:05.740  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.740  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-28 12:07:05.740  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:07:05.740  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:07:05.740  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-28 12:07:05.741  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:07:05.741  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-28 12:07:05.741  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 12:07:05.743  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:05.744  2557  2772 D BtGatt.GattService: stopScan() - queue size =1
,07-28 12:07:05.745  2557  2771 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-28 12:07:05.745  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 12:07:05.745  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-28 12:07:05.745  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-28 12:07:05.745  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 12:07:05.745  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 12:07:05.746  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.747  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 12:07:05.747  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:07:05.747  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:07:05.748  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:05.749  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.749  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.749  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:05.749  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
,07-28 12:07:05.749  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:05.750  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.750  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.750  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:07:05.750  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.750  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:05.750  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.751  3701  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-28 12:07:05.753  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:05.760  2557  2617 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:07:05.760  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:05.761  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:07:05.765  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.765  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:05.766  2557  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:07:05.766  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:07:05.766  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.768  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:07:05.768  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:05.769  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:07:05.769  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:05.773  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:05.774  2557  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:07:05.774  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.774  2557  2634 D BtGatt.ScanManager: stopping BLe Batch
,07-28 12:07:05.777  3701  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-28 12:07:05.777  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:07:05.780  2557  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-28 12:07:05.781  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.781  2557  2634 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 12:07:05.786  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:07:05.786  2557  2617 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:07:05.786  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-28 12:07:05.786  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.786  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:07:05.792  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:07:05.792  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:07:05.792  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:07:05.792  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:05.795  2557  2771 D BtGatt.GattService: registerClient() - UUID=1c54f840-aa78-4b05-b018-14d3c107235f
,07-28 12:07:05.796  2557  2617 D BtGatt.GattService: onClientRegistered() - UUID=1c54f840-aa78-4b05-b018-14d3c107235f, clientIf=5
,07-28 12:07:05.796  3701  3711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:07:05.797  2557  2763 D BtGatt.GattService: start scan with filters
,07-28 12:07:05.800  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:07:05.800  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:07:05.800  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:07:05.800  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 12:07:05.800  2557  2634 D BtGatt.ScanManager: handling starting scan
,07-28 12:07:05.802  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:07:05.802  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:07:05.802  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-28 12:07:05.803  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 12:07:05.805  3701  3701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:07:05.805  3701  3701 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-28 12:07:05.805  3701  3748 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 12:07:05.807  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:07:05.807  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.807  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.807  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 12:07:05.807  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-28 12:07:05.807  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:07:05.807  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-28 12:07:05.807  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:07:05.807  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-28 12:07:05.808  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 12:07:05.808  2557  2617 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 12:07:05.808  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.808  3701  3748 D BluetoothAdapter: STATE_ON
07-28 12:07:05.809  2557  2634 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 12:07:05.809  2557  2571 D BtGatt.GattService: stopScan() - queue size =1
07-28 12:07:05.810  2557  2570 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:07:05.810  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped,
07-28 12:07:05.810  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-28 12:07:05.810  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:07:05.810  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 12:07:05.810  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 12:07:05.811  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.812  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 12:07:05.812  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:07:05.812  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:07:05.812  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:07:05.813  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:05.813  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.813  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:05.813  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false,
07-28 12:07:05.813  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:05.813  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.813  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:07:05.813  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.813  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list,
07-28 12:07:05.813  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.814  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.814  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.814  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.815  2557  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:07:05.815  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.815  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.815  2557  2634 D BtGatt.ScanManager: Starting BLE batch scan
,07-28 12:07:05.815  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.815  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.815  2557  2634 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:07:05.815  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.816  3701  3748 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:07:05.817  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:05.822  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:07:05.823  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:07:05.823  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:05.825  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:05.825  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:07:05.825  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:07:05.826  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.825  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:05.826  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:07:05.827  2557  2617 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:07:05.827  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.830  3701  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-28 12:07:05.830  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:07:05.833  2557  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-28 12:07:05.833  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.834  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:07:05.835  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:07:05.835  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:07:05.838  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:07:05.838  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-28 12:07:05.838  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:07:05.839  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:05.841  2557  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
,07-28 12:07:05.841  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.841  2557  2634 D BtGatt.ScanManager: stopping BLe Batch
,07-28 12:07:05.841  2557  2571 D BtGatt.GattService: registerClient() - UUID=7afe00d9-dc57-41dd-98ef-f7f2302de481
,07-28 12:07:05.843  2557  2617 D BtGatt.GattService: onClientRegistered() - UUID=7afe00d9-dc57-41dd-98ef-f7f2302de481, clientIf=5
,07-28 12:07:05.843  3701  3712 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:07:05.844  2557  2570 D BtGatt.GattService: start scan with filters
,07-28 12:07:05.847  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:07:05.847  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:07:05.847  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-28 12:07:05.847  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 12:07:05.849  2557  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:07:05.849  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.850  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:07:05.850  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 12:07:05.850  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:07:05.851  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-28 12:07:05.852  2557  2634 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 12:07:05.854  3701  3748 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:07:05.854  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.854  3701  3701 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:07:05.854  3701  3701 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-28 12:07:05.854  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.855  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.855  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 12:07:05.855  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:07:05.855  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:07:05.855  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:07:05.855  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:07:05.855  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:07:05.855  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 12:07:05.856  3701  3748 D BluetoothAdapter: STATE_ON
07-28 12:07:05.856  2557  2570 D BtGatt.GattService: stopScan() - queue size =0
,07-28 12:07:05.857  2557  2772 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:07:05.857  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:07:05.857  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 12:07:05.857  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:07:05.857  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 12:07:05.857  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 12:07:05.858  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.858  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 12:07:05.858  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:07:05.858  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:07:05.858  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:05.859  2557  2617 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:07:05.859  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:05.860  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:05.860  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:07:05.860  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:05.860  3701  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
07-28 12:07:05.860  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.860  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.860  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.860  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:05.860  2557  2634 D BtGatt.ScanManager: handling starting scan
07-28 12:07:05.860  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.860  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:05.861  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.861  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.861  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.861  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:07:05.861  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.865  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.865  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.866  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:05.866  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:07:05.866  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:07:05.866  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.867  3701  3748 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,07-28 12:07:05.867  2557  2617 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-28 12:07:05.867  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.867  2557  2634 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 12:07:05.868  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:07:05.868  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.868  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.868  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:05.868  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.868  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.868  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
,07-28 12:07:05.868  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.868  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.868  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.868  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.868  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.868  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.868  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.869  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.869  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.870  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:07:05.870  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.870  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:07:05.870  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.870  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.870  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:07:05.871  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.871  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.871  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.871  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.871  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.871  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list,
07-28 12:07:05.871  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:07:05.871  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.871  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.871  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.871  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.872  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.872  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:07:05.872  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.872  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.872  3701  3748 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-28 12:07:05.873  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:07:05.873  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:07:05.873  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.873  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
07-28 12:07:05.873  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.873  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.873  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.873  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
,07-28 12:07:05.873  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.873  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.873  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.873  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.873  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:05.873  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:05.874  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.874  2557  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:07:05.874  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.874  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.874  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.874  2557  2634 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:07:05.874  2557  2634 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:07:05.874  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.875  3701  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:07:05.875  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.875  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.875  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.875  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.875  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.875  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.875  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.875  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.875  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.876  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.876  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.876  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.876  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.876  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.877  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.877  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.877  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.877  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.877  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:07:05.877  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 12:07:05.877  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:07:05.877  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:07:05.878  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:07:05.878  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:07:05.878  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.878  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.878  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.878  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.878  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.878  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.878  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.878  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.878  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.878  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.878  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.878  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.878  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.878  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.879  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.879  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.879  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.879  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.880  3701  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:07:05.880  3701  3748 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:07:05.881  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:07:05.884  3701  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:07:05.884  3701  3748 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:07:05.884  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:07:05.885  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:07:05.886  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:07:05.886  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:07:05.886  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:07:05.886  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:07:05.886  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:07:05.886  3701  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:07:05.886  3701  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:07:05.886  3701  3748 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:07:05.886  3701  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:07:05.886  3701  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:07:05.886  3701  3748 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:07:05.887  3701  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:07:05.887  3701  3748 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:07:05.887  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:07:05.888  2557  2617 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:07:05.888  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.890  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:07:05.890  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:07:05.891  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:07:05.891  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 12:07:05.891  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:07:05.891  3701  3748 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:07:05.891  3701  3748 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:07:05.892  3701  3748 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:07:05.892  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.892  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.892  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.893  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.893  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.893  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.893  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:07:05.893  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.893  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.894  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.894  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.894  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.894  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.894  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.894  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.895  3701  3754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 386
07-28 12:07:05.895  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.896  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.896  2557  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:07:05.896  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.896  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.896  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.897  3701  3748 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:07:05.897  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.897  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.897  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.897  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.897  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.897  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.897  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.897  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.897  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.897  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.897  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.897  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.897  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.897  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.898  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.898  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.898  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.898  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.899  3701  3748 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:07:05.899  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.899  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.899  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.899  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.899  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.899  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.899  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.899  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.899  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.899  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.899  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.899  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.899  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.899  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.900  3701  3753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 386)
07-28 12:07:05.900  3701  3753 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 386)
07-28 12:07:05.901  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.901  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.901  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.901  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.901  3701  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:07:05.901  3701  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:07:05.901  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:07:05.901  3701  3748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:07:05.902  3701  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:07:05.902  3701  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:07:05.902  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:07:05.902  3701  3748 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:07:05.902  3701  3748 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:07:05.902  3701  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:07:05.902  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:07:05.902  3701  3748 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:07:05.902  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.902  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.902  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.902  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.902  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.902  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.902  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.902  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.903  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.903  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.903  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.903  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.903  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.903  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.904  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.904  2557  2617 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:07:05.904  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.904  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.904  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.904  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.904  2557  2634 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:07:05.904  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.904  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.904  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.904  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.904  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
07-28 12:07:05.905  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.905  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.905  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.905  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.905  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.905  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.905  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.905  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.905  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.905  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.905  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.905  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.905  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.905  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.905  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.905  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.906  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.906  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.906  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.906  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.906  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.906  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.906  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.906  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.906  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.906  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.906  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.906  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.907  3701  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:07:05.908  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:05.908  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:07:05.909  3701  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:07:05.909  3701  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:07:05.909  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:07:05.909  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:07:05.909  3701  3701 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:07:05.909  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.909  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:07:05.909  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:07:05.909  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:07:05.909  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.910  3701  3748 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:07:05.910  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.910  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.910  3701  3701 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 12:07:05.910  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:07:05.910  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:07:05.910  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:07:05.910  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.910  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.910  3701  3755 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:07:05.910  3701  3755 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:07:05.911  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.911  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.911  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:05.911  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.911  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.911  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.911  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.911  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.911  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.911  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.911  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.911  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.911  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:05.911  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.911  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.911  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.911  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.911  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:05.911  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.911  2557  2617 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:07:05.911  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.911  3701  3701 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:07:05.912  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.912  2557  2634 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 12:07:05.912  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.912  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.912  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.913  3701  3748 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:07:05.913  3701  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:07:05.913  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:07:05.913  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:07:05.913  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.913  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.913  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.913  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.913  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.913  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.913  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.913  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.914  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.914  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.914  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.914  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.914  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.914  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.914  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.914  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.915  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.915  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.918  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.918  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.918  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.918  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.918  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.918  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.918  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.918  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.918  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.918  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.918  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.918  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.918  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.919  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.920  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.920  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.920  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.920  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.920  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:05.921  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:05.921  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:05.921  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:05.921  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.921  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.921  3701  3748 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ce69c74 not in the list
07-28 12:07:05.921  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.921  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.921  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:05.921  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.921  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.921  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:05.921  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:05.922  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:05.922  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:05.922  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:05.922  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@794259d not in the list
07-28 12:07:05.922  3701  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 12:07:05.922  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:07:05.923  3701  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:07:05.923  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:07:05.923  3701  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:07:05.923  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:07:05.924  2557  2617 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-28 12:07:05.924  2557  2617 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:05.924  2557  2617 D BtGatt.GattService: current time is 282658496292
07-28 12:07:05.924  2557  2617 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -106, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
07-28 12:07:05.924  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:07:05.924  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-28 12:07:05.925  3701  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 12:07:05.925  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:07:05.925  2557  2617 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
07-28 12:07:05.925  3701  3748 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:07:05.925  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:07:05.925  3701  3748 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:07:05.925  3701  3748 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-28 12:07:05.925  3701  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:07:05.925  3701  3748 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-28 12:07:05.926  3701  3748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 12:07:05.926  3701  3748 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:07:05.926  3701  3748 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:07:05.926  3701  3748 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 12:07:05.927  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:05.927  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e786537 added. We now have 2 listener(s)
07-28 12:07:05.927  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:05.928  3701  3748 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:07:05.929   872  1764 D WifiService: setWifiEnabled: true pid=3701, uid=10000
07-28 12:07:05.929   872  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:07:05.930  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:05.930  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7a40aa4 added. We now have 3 listener(s)
07-28 12:07:05.930  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:05.935  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:05.935  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@aeeb00d added. We now have 4 listener(s)
07-28 12:07:05.935  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:05.937  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:05.937  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8531bc2 added. We now have 5 listener(s)
07-28 12:07:05.937  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:05.939   872  1757 D WifiService: setWifiEnabled: false pid=3701, uid=10000
07-28 12:07:05.939   872  1757 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-28 12:07:05.948  2557  2613 D BluetoothAdapterState: Current state: ON, message: 23
07-28 12:07:05.948  2557  2613 D BluetoothAdapterProperties: Setting state to 13
07-28 12:07:05.948  2557  2613 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:07:05.948  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:05.949  2557  2613 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:07:05.949  2557  2613 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:07:05.950  2557  2617 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:07:05.951  2557  2557 D BluetoothMapService: onReceive
07-28 12:07:05.951  2557  2557 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:07:05.951  2557  2557 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:07:05.952  2557  2557 D BluetoothMapService: MAP Service closeService in
07-28 12:07:05.952  2557  2557 D BluetoothMapMasInstance0: MAP Service shutdown
07-28 12:07:05.952  2557  2557 D ObexServerSockets0: shutdown(block = true)
07-28 12:07:05.952  2557  2613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-28 12:07:05.952  2557  2773 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-28 12:07:05.952  2557  2557 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 12:07:05.953  2557  2557 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-28 12:07:05.953  2557  2760 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-28 12:07:05.953  2557  2774 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-28 12:07:05.953  2557  2557 I BtOppRfcommListener: stopping Accept Thread
07-28 12:07:05.954  2557  3292 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:07:05.954  2557  3292 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:07:05.956  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:05.957  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:07:05.957  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:05.957  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.958  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:05.960  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.961  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-28 12:07:05.962   872  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:07:05.962   872  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-28 12:07:05.962   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:07:05.962   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:07:05.963  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.965   872   885 I ActivityManager: Start proc 3758:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-28 12:07:05.968   872  1315 E native  : do suspend true
07-28 12:07:05.970  2557  2557 D HeadsetService: Received stop request...Stopping profile...
07-28 12:07:05.972   872   872 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:05.972  1360  3700 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:05.972   872   872 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:05.972  1745  1755 D BluetoothHeadset: Proxy object disconnected
,07-28 12:07:05.973   872   872 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:05.974  1360  1360 D HeadsetProfile: Bluetooth service disconnected
07-28 12:07:05.976  2557  2557 D A2dpService: Received stop request...Stopping profile...
07-28 12:07:05.976  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:05.976  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:07:05.976  2557  2766 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:07:05.977  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:05.977  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:05.978   872   872 D BluetoothA2dp: Proxy object disconnected
07-28 12:07:05.978  2557  2557 D HidService: Received stop request...Stopping profile...
07-28 12:07:05.978  2557  2557 D HidService: Stopping Bluetooth HidService
07-28 12:07:05.979  1360  1360 D BluetoothA2dp: Proxy object disconnected
07-28 12:07:05.979  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.980   872  1997 D DhcpClient: Clearing IP address
07-28 12:07:05.980  1360  1360 D BluetoothInputDevice: Proxy object disconnected
,07-28 12:07:05.980   372   870 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:07:05.980  1360  1360 D HidProfile: Bluetooth service disconnected
07-28 12:07:05.982  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.982  2557  2557 D HealthService: Received stop request...Stopping profile...
07-28 12:07:05.984   372   870 D CommandListener: Setting iface cfg
07-28 12:07:05.984  2557  2557 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:05.984  2557  2557 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:05.985  2557  2557 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:05.985  2557  2557 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:05.985  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:05.986  2557  2557 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:07:05.987  2557  2557 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:07:05.987  2557  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:05.987  2557  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:05.987  2557  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:05.987   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-28 12:07:05.987  2557  2617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-28 12:07:05.987   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-28 12:07:05.987  2557  2617 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-28 12:07:05.988  2557  2557 D PanService: Received stop request...Stopping profile...
,07-28 12:07:05.990   442   442 E Parcel  : Reading a NULL string not supported here.
07-28 12:07:05.991   872  1315 D WifiStateMachine: Start Disconnecting Watchdog 1
07-28 12:07:05.992   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:07:05.992   872  1315 E native  : do suspend true
07-28 12:07:05.993  2557  2557 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:05.993  2557  2557 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:05.993  2557  2557 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:05.993  2557  2557 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:05.993   872  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-28 12:07:05.994  2557  2557 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:07:05.994  2557  2557 D BluetoothMapService: stop()
07-28 12:07:05.994  2557  2557 D BluetoothMapAppObserver: deinitObservers()
07-28 12:07:05.994  2557  2557 D BluetoothMapAppObserver: removeReceiver()
07-28 12:07:05.997  2557  2557 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:05.997  2557  2557 V BluetoothAdapterState: isTurningOn()=false
,07-28 12:07:05.997  2557  2557 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:05.998  2557  2557 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:05.998  2557  2557 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:07:05.998  1527  2307 V NativeCrypto: Read error: ssl=0x9b4a0000: I/O error during system call, Connection timed out
07-28 12:07:05.998  2557  2557 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:07:05.999  2557  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:05.999  2557  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:05.999  2557  2753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:07:05.999  2557  2753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:07:05.999  2557  2753 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:07:05.999  2557  2753 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:07:05.999  2557  2617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 12:07:06.000  2557  2617 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 12:07:06.000  2557  2557 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:06.000  2557  2557 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:06.000  2557  2557 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:06.000  2557  2557 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:06.000  2557  2557 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:07:06.000  2557  2617 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-28 12:07:06.001  2557  2557 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:07:06.001  2557  2557 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:06.001  2557  2557 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:06.001  2557  2557 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:06.001  2557  2557 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:06.002  2557  2557 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:07:06.002  2557  2557 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:07:06.003  2557  2557 D BluetoothMapService: MAP Service closeService in
07-28 12:07:06.003  2557  2557 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:06.003  2557  2557 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:06.003  2557  2557 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:06.003  2557  2557 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:06.003  2557  2613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,07-28 12:07:06.003  2557  2613 D BluetoothAdapterProperties: Setting state to 15
07-28 12:07:06.003  2557  2557 D BluetoothMapService: cleanup()
07-28 12:07:06.003  2557  2613 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-28 12:07:06.003  2557  2557 D BluetoothMapService: MAP Service closeService in
07-28 12:07:06.004  1360  1396 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:07:06.004  2557  2613 I BluetoothAdapterState: Entering BleOnState
07-28 12:07:06.005  1360  3700 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:07:06.007  1360  1377 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:07:06.008   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:06.008   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:07:06.008  1360  1796 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:07:06.008   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:06.008  1360  1396 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:07:06.009   872  2003 D DhcpClient: Receive thread stopped
07-28 12:07:06.010   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 12:07:06.010  1360  3700 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:06.010  1745  1755 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:06.011  2557  2613 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-28 12:07:06.011  2557  2613 D BluetoothAdapterProperties: Setting state to 16
07-28 12:07:06.011  2557  2613 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-28 12:07:06.012  2557  2613 D BluetoothAdapterProperties: onBleDisable
07-28 12:07:06.012  2557  2613 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:07:06.012  2557  2614 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-28 12:07:06.013  2557  2753 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:07:06.013  2557  2753 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:06.013  2557  2617 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:07:06.014  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:06.014  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:06.014  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:06.014  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:06.017  1527  2307 V NativeCrypto: SSL shutdown failed: ssl=0x9b4a0000: I/O error during system call, Broken pipe
07-28 12:07:06.019  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:06.019  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:06.020  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:06.020  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:06.021  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:06.022  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:06.029   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:06.046  3758  3758 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-28 12:07:06.047   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:06.048   872  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-28 12:07:06.048   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:07:06.048   372   870 D CommandListener: Clearing all IP addresses on wlan0
07-28 12:07:06.049   872   889 D Tethering: MasterInitialState.processMessage what=3
07-28 12:07:06.052   872  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-28 12:07:06.052  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:06.054  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:06.058  3278  3278 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@4125a29 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,07-28 12:07:06.067  1810  1810 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-28 12:07:06.070   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:07:06.072  1974  2102 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:07:06.072   872  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:07:06.073  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:06.073  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:06.075  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:06.075  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:06.078  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:06.078  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:06.079  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:06.079  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:06.088  3758  3758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:07:06.093   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@60f6c54:true
,07-28 12:07:06.094  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:07:06.102   372   870 E Netd    : netlink response contains error (No such file or directory)
,07-28 12:07:06.103   872  1317 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-28 12:07:06.107   872  3091 I ActivityManager: Start proc 3778:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-28 12:07:06.116  3758  3758 D LocalBluetoothProfileManager: Adding local MAP profile
07-28 12:07:06.118  3758  3758 D BluetoothMap: Create BluetoothMap proxy object
,07-28 12:07:06.122  3758  3758 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-28 12:07:06.128  3758  3758 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:07:06.132   872  2988 I ActivityManager: Killing 2859:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-28 12:07:06.152  3778  3778 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-28 12:07:06.174  1527  1996 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-28 12:07:06.218  2557  2617 I bt_hci  : shut_down
,07-28 12:07:06.230  2557  2637 D bt_hwcfg: hw_epilog_process
,07-28 12:07:06.230  2557  2637 I bt_vendor: low_power_mode_cb
,07-28 12:07:06.248  2557  2637 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-28 12:07:06.248  2557  2637 I bt_vendor: epilog_cb
07-28 12:07:06.248  2557  2637 I bt_hci  : epilog_finished_callback
,07-28 12:07:06.254  2557  2617 I bt_hci_h4: hal_close
,07-28 12:07:06.255  2557  2617 I bt_userial_vendor: device fd = 51 close
,07-28 12:07:06.319  3778  3778 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:07:06.319  3778  3778 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:07:06.319  3778  3778 D StrictMode: StrictMode policy violation; ~duration=107 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:06.319  3778  3778 D StrictMode: StrictMode policy violation; ~duration=106 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-28 12:07:06.319  3,778  3778 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:07:06.319  3778  3778 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.k.d(PG:583)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.319  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:06.320  3778  3778 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at and,roid.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:06.320  3778  3778 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.io.File.exists(File.java:361)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.320  3778  3778 D StrictMod,e: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:06.320  3778  3778 D StrictMode: StrictMode policy violation; ~duration=76 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:06.320  3778  3778 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:06.323  3758  3758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:07:06.331  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:07:06.339  3758  3758 D DockEventReceiver: finishStartingService: stopping service
07-28 12:07:06.343   872  1735 I ActivityManager: Killing 3278:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-28 12:07:06.440  2557  2614 D bt_stack_manager: event_shut_down_stack finished.
,07-28 12:07:06.442  2557  2613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-28 12:07:06.446  2557  2557 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:07:06.446  2557  2613 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-28 12:07:06.447  2557  2557 D BtGatt.GattService: Received stop request...Stopping profile...
,07-28 12:07:06.447  2557  2557 D BtGatt.GattService: stop()
07-28 12:07:06.447  2557  2557 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 12:07:06.448  1949  1949 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 12:07:06.451  2557  2557 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:06.451  2557  2557 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:06.452  2557  2557 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:07:06.452  2557  2557 V BluetoothAdapterState: isBleTurningOff()=true
,07-28 12:07:06.452  1949  1949 D SystemUpdateService: onCreate
,07-28 12:07:06.453  2557  2613 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
07-28 12:07:06.453  2557  2613 D BluetoothAdapterProperties: Setting state to 10
,07-28 12:07:06.454  2557  2613 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,07-28 12:07:06.455  2557  2613 I BluetoothAdapterState: Entering OffState
07-28 12:07:06.455   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-28 12:07:06.456  1949  1949 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 12:07:06.486  2557  2557 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-28 12:07:06.486  2557  2557 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-28 12:07:06.486  2557  2557 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:07:06.487  2557  2614 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-28 12:07:06.490  2557  2614 D bt_stack_manager: event_clean_up_stack finished.
,07-28 12:07:06.492  1949  3809 I SystemUpdateService: active receiver: enabled
,07-28 12:07:06.493  2557  2557 I art     : System.exit called, status: 0
,07-28 12:07:06.493  2557  2557 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:07:06.500  1949  1949 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-28 12:07:06.505  1949  2347 I iu.UploadsManager: num queued entries: 0
,07-28 12:07:06.505  1949  2347 I iu.UploadsManager: num updated entries: 0
,07-28 12:07:06.519  1949  3809 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:07:06.522  1949  1949 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 12:07:06.524  1949  1949 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 12:07:06.526  1949  2347 I iu.SyncManager: NEXT; no task
,07-28 12:07:06.529  1949  3809 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-28 12:07:06.529  1949  3809 I SystemUpdateService: now status is 0 (complete)
,07-28 12:07:06.529  1949  3809 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-28 12:07:06.529  1949  3809 I SystemUpdateService: file has been verified
07-28 12:07:06.530  1949  3809 I SystemUpdateService: OTA package size = 12249756
,07-28 12:07:06.547  1949  3809 I SystemUpdateService: showing system update notification
,07-28 12:07:06.587   872  1683 I ActivityManager: Start proc 3813:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
07-28 12:07:06.589   872  1724 I ActivityManager: Process com.android.bluetooth (pid 2557) has died
,07-28 12:07:06.615  1949  1949 D SystemUpdateService: onDestroy
,07-28 12:07:06.633  3778  3798 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-28 12:07:06.646  3813  3813 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
,07-28 12:07:06.651  3813  3813 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:07:06.659  3813  3813 D SprintDMHelper: simOperator: 
,07-28 12:07:06.659  3813  3813 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 12:07:06.669   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@432ec52:true
,07-28 12:07:06.675   872  1739 I ActivityManager: Start proc 3827:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,07-28 12:07:06.754  3362  3841 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-28 12:07:06.777   872  1399 I ActivityManager: Start proc 3842:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-28 12:07:06.779   872  1724 I ActivityManager: Killing 3324:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-28 12:07:06.851  3842  3842 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-28 12:07:06.915  3842  3842 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-28 12:07:06.915  3842  3842 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-28 12:07:06.915  3842  3842 I GAv4    :   adb logcat -s GAv4
,07-28 12:07:06.931  3842  3842 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-28 12:07:06.939  3842  3842 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-28 12:07:06.969  3842  3859 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-28 12:07:07.082  3842  3842 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-28 12:07:07.125  3842  3842 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-28 12:07:07.133  3842  3842 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3865-3867)
,07-28 12:07:07.134  3842  3842 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:07:07.147  3842  3842 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {fc7d75b}
,07-28 12:07:07.148  3842  3842 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-28 12:07:07.148  3842  3842 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:07:07.157  3842  3842 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:07:07.158  3842  3842 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:07:07.182  3842  3842 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-28 12:07:07.199  3842  3842 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-28 12:07:07.199  3842  3842 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-28 12:07:07.199  3842  3842 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-28 12:07:07.199  3842  3842 I Adreno  : Build Date                       : 10/20/15
07-28 12:07:07.199  3842  3842 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-28 12:07:07.199  3842  3842 I Adreno  : Local Branch                     : M14
07-28 12:07:07.199  3842  3842 I Adreno  : Remote Branch                    : 
07-28 12:07:07.199  3842  3842 I Adreno  : Remote Branch                    : 
07-28 12:07:07.199  3842  3842 I Adreno  : Reconstruct Branch               : 
,07-28 12:07:07.262  3842  3842 I NSApplication: Starting up...
,07-28 12:07:07.249  3842  3888 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-28 12:07:07.285   872   882 I ActivityManager: Start proc 3893:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-28 12:07:07.286   872   882 I ActivityManager: Killing 1699:android.process.acore/u0a5 (adj 15): empty #17
,07-28 12:07:07.365  3893  3893 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-28 12:07:07.552   872  1739 I ActivityManager: Killing 3543:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-28 12:07:07.572  3442  3451 W art     : Suspending all threads took: 6.188ms
,07-28 12:07:07.635   872  1739 I ActivityManager: Start proc 3907:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-28 12:07:07.717  3907  3907 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-28 12:07:07.765  3907  3907 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-28 12:07:07.780   872  1724 I ActivityManager: Killing 3558:com.android.musicfx/u0a18 (adj 15): empty #17
,07-28 12:07:08.963   872   882 D WifiService: setWifiEnabled: true pid=3701, uid=10000
,07-28 12:07:08.963   872   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:07:08.975   872  1315 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:07:08.983  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:08.983  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:08.984  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:08.984  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:08.987  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:08.988  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:08.988  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:08.988  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:09.006   872  1315 D WifiConfigStore: loaded 0 passpoint configs
,07-28 12:07:09.007   872  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:07:09.007   872  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-28 12:07:09.008   872  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-28 12:07:09.009   872  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:07:09.009   872  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-28 12:07:09.009   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-28 12:07:09.009   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-28 12:07:09.025   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-28 12:07:09.025   872  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:07:09.026   372   870 D CommandListener: Setting iface cfg
,07-28 12:07:09.027   872  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
07-28 12:07:09.027   872  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:07:09.036   872  1314 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:07:09.036   872  1315 E native  : do suspend true
,07-28 12:07:09.037   872  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-28 12:07:09.062   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:07:10.430   872  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:07:10.475   872  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.50 rxSuccessRate=12.25 delta 1000 -> 994
,07-28 12:07:10.477   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-28 12:07:10.478   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:07:10.502   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-28 12:07:10.587   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-28 12:07:10.593  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-28 12:07:11.018  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-28 12:07:11.056  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-28 12:07:11.056  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-28 12:07:11.063   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:07:11.082   872  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:07:11.083   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:07:11.083   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,07-28 12:07:11.111   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:07:11.130   372   870 D CommandListener: Setting iface cfg
,07-28 12:07:11.130   872  1315 D WifiStateMachine: Start Dhcp Watchdog 2
,07-28 12:07:11.137   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-28 12:07:11.184   872  3944 D DhcpClient: Receive thread started
,07-28 12:07:11.265   872  1315 E native  : do suspend false
,07-28 12:07:11.275   872  1997 D DhcpClient: Broadcasting DHCPDISCOVER
,07-28 12:07:11.290   872  3944 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172534, domain null
,07-28 12:07:11.291   872  1997 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172534 seconds
,07-28 12:07:11.293   872  1997 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-28 12:07:11.305   872  3944 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-28 12:07:11.306   872  1997 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-28 12:07:11.310   372   870 D CommandListener: Setting iface cfg
,07-28 12:07:11.319   872  1997 D DhcpClient: Scheduling renewal in 86399s
,07-28 12:07:11.319   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
07-28 12:07:11.323   872  1315 E native  : do suspend true
,07-28 12:07:11.344   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-28 12:07:11.347   872  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,07-28 12:07:11.349   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-28 12:07:11.351   872  1317 D ConnectivityService: Adding iface wlan0 to network 101
,07-28 12:07:11.360   872  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:07:11.415   872  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-28 12:07:11.415   872  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-28 12:07:11.418   872  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-28 12:07:11.419   872  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-28 12:07:11.421   872  1317 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-28 12:07:11.444   872  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-28 12:07:11.449   872  1317 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-28 12:07:11.449   872  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-28 12:07:11.450   872  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,07-28 12:07:11.450   872  1317 D ConnectivityService:    accepting network in place of null
07-28 12:07:11.450   872  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-28 12:07:11.451   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-28 12:07:11.451   872  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:07:11.464   872  3943 D NetlinkSocketObserver: NeighborEvent{elapsedMs=288197, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-28 12:07:11.492   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:11.528   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:11.533   872  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-28 12:07:11.533   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:07:11.536   872  3942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.14,2a00:1450:4001:80d::200e,
,07-28 12:07:11.544   872   889 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:07:11.542   872  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-28 12:07:11.562  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:11.563  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:07:11.563  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:11.564  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:07:11.567  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:11.568  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:07:11.568  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:11.568  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:07:11.571  1949  1949 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 12:07:11.574  1949  1949 D SystemUpdateService: onCreate
,07-28 12:07:11.576  1810  1810 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-28 12:07:11.577  1949  1949 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 12:07:11.580  1949  3954 I SystemUpdateService: active receiver: enabled
,07-28 12:07:11.585  1949  3954 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:07:11.588  1949  3954 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-28 12:07:11.588  1949  3954 I SystemUpdateService: now status is 0 (complete)
07-28 12:07:11.588  1949  3954 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-28 12:07:11.588  1949  3954 I SystemUpdateService: file has been verified
07-28 12:07:11.588  1949  3954 I SystemUpdateService: OTA package size = 12249756
,07-28 12:07:11.591  1949  3954 I SystemUpdateService: showing system update notification
,07-28 12:07:11.598  1949  1949 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-28 12:07:11.601  1949  2347 I iu.UploadsManager: num queued entries: 0
,07-28 12:07:11.602  1949  2347 I iu.UploadsManager: num updated entries: 0
,07-28 12:07:11.603  1949  2347 I iu.SyncManager: NEXT; no task
,07-28 12:07:11.604  1949  1949 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-28 12:07:11.604  1949  3958 I MDM     : [215] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-28 12:07:11.604  1949  3958 W BaseAppContext: Using Auth Proxy for data requests.
,07-28 12:07:11.606  1949  1949 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 12:07:11.608  1949  3958 V GoogleAuthProtoRequest: [215] a.<init>: mAccountName set to: thalitester@gmail.com
,07-28 12:07:11.609  3813  3813 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:07:11.610  1949  1949 D SystemUpdateService: onDestroy
,07-28 12:07:11.614  3813  3813 D SprintDMHelper: simOperator: 
,07-28 12:07:11.614  3813  3813 D SprintDMReceiver: Not Sprint UICC, don't do anything.
07-28 12:07:11.615   872  3942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:07:11 GMT], X-Android-Received-Millis=[1469700431614], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469700431581]}
,07-28 12:07:11.615  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:07:11.617   872  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-28 12:07:11.617   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
07-28 12:07:11.617   872  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-28 12:07:11.618   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 12:07:11.620  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:07:11.651  1527  1900 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-28 12:07:11.651  1527  1900 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-28 12:07:11.651  1527  1900 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-28 12:07:11.651  1527  1900 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:07:11.664  1949  3958 E MDM     : [215] SitrepService.a: Error sending sitrep.
,07-28 12:07:11.740  3362  3962 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-28 12:07:11.744   872  1739 I ActivityManager: Killing 2065:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-28 12:07:11.969   872   883 D WifiService: setWifiEnabled: false pid=3701, uid=10000
07-28 12:07:11.969   872   883 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:07:11.980  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-28 12:07:11.982   872  1315 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-28 12:07:11.982   872  1315 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,07-28 12:07:11.982   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:07:11.982   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:07:12.006   872  1315 E native  : do suspend true
,07-28 12:07:12.016   872  1997 D DhcpClient: Clearing IP address
,07-28 12:07:12.017   372   870 D CommandListener: Setting iface cfg
,07-28 12:07:12.021   372   870 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:07:12.023   872  3944 D DhcpClient: Receive thread stopped
,07-28 12:07:12.025  1527  3966 V NativeCrypto: Read error: ssl=0x9b02f600: I/O error during system call, Connection timed out
,07-28 12:07:12.027  1527  3966 V NativeCrypto: SSL shutdown failed: ssl=0x9b02f600: I/O error during system call, Broken pipe
,07-28 12:07:12.030   872  2988 D ConnectivityService: reportNetworkConnectivity(101, false) by 10011
,07-28 12:07:12.031   872  3942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10011
,07-28 12:07:12.032   872  3942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.18.14,2a00:1450:4001:80d::200e
,07-28 12:07:12.039   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,07-28 12:07:12.040   872  1315 D WifiStateMachine: Start Disconnecting Watchdog 2
07-28 12:07:12.040   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
07-28 12:07:12.041   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:07:12.041   872  1315 E native  : do suspend true
,07-28 12:07:12.046   442   442 E Parcel  : Reading a NULL string not supported here.
07-28 12:07:12.054   872  1317 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-28 12:07:12.054   872  3942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:80d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,07-28 12:07:12.057   372   870 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:07:12.085   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:12.114   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:12.117   872  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:07:12.116   872  1317 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-28 12:07:12.117   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:07:12.122   872   889 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:07:12.130  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:12.131  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:12.131  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:12.131  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:12.134  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:12.134  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:12.135  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:07:12.135  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:12.139  1810  1810 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
07-28 12:07:12.152   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:07:12.148  1949  1949 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 12:07:12.156  1974  2102 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:07:12.156  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:12.157  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:12.157  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:12.157  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:12.157  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:12.158  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:12.158  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:12.158   872  1315 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:07:12.161  1949  1949 D SystemUpdateService: onCreate
,07-28 12:07:12.167  1949  1949 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 12:07:12.177  1949  1949 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-28 12:07:12.181  1949  2347 I iu.UploadsManager: num queued entries: 0
,07-28 12:07:12.181  1949  2347 I iu.UploadsManager: num updated entries: 0
,07-28 12:07:12.182  1949  3975 I SystemUpdateService: active receiver: enabled
,07-28 12:07:12.184  1949  1949 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
07-28 12:07:12.185  1949  1949 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
07-28 12:07:12.186  1949  2347 I iu.SyncManager: NEXT; no task
,07-28 12:07:12.190  3813  3813 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:07:12.192  1949  3975 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:07:12.194  1949  3975 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-28 12:07:12.194  1949  3975 I SystemUpdateService: now status is 0 (complete)
07-28 12:07:12.195  1949  3975 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-28 12:07:12.195  1949  3975 I SystemUpdateService: file has been verified
07-28 12:07:12.195  3813  3813 D SprintDMHelper: simOperator: 
07-28 12:07:12.195  3813  3813 D SprintDMReceiver: Not Sprint UICC, don't do anything.
07-28 12:07:12.200  1949  3975 I SystemUpdateService: OTA package size = 12249756
,07-28 12:07:12.204   372   870 E Netd    : netlink response contains error (No such file or directory)
,07-28 12:07:12.205   872  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-28 12:07:12.211  3362  3979 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-28 12:07:12.228  1949  3975 I SystemUpdateService: showing system update notification
,07-28 12:07:12.243  1949  1949 D SystemUpdateService: onDestroy
,07-28 12:07:12.533   872  1317 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-28 12:07:15.025   872   889 I ActivityManager: Start proc 3982:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-28 12:07:15.147  3982  3982 D AdapterServiceConfig: Adding HeadsetService
,07-28 12:07:15.147  3982  3982 D AdapterServiceConfig: Adding A2dpService
,07-28 12:07:15.147  3982  3982 D AdapterServiceConfig: Adding HidService
,07-28 12:07:15.147  3982  3982 D AdapterServiceConfig: Adding HealthService
,07-28 12:07:15.148  3982  3982 D AdapterServiceConfig: Adding PanService
,07-28 12:07:15.148  3982  3982 D AdapterServiceConfig: Adding GattService
,07-28 12:07:15.149  3982  3982 D AdapterServiceConfig: Adding BluetoothMapService
,07-28 12:07:15.166   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7c69727:true
,07-28 12:07:15.166  3982  3982 D BluetoothAdapterState: make() - Creating AdapterState
,07-28 12:07:15.171  3982  3982 I bt_bluedroid: init
,07-28 12:07:15.171  3982  3994 I BluetoothAdapterState: Entering OffState
,07-28 12:07:15.177  3982  3995 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:07:15.178  3982  3995 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:07:15.178  3982  3995 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 12:07:15.178  3982  3995 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
07-28 12:07:15.181  3982  3982 I bt_bluedroid: get_profile_interface socket
07-28 12:07:15.183  3982  3982 I bt_bluedroid: get_profile_interface sdp
07-28 12:07:15.186  3982  3998 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 12:07:15.189  3982  3998 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:07:15.190  3982  3993 I bt_bluedroid: config_hci_snoop_log
,07-28 12:07:15.193   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-28 12:07:15.200  3982  3994 D BluetoothAdapterState: Current state: OFF, message: 0
,07-28 12:07:15.201  3982  3994 D BluetoothAdapterProperties: Setting state to 14
07-28 12:07:15.201  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-28 12:07:15.206  3982  3994 D BluetoothBondStateMachine: make
,07-28 12:07:15.208  3982  3999 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:07:15.217  3982  3982 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
07-28 12:07:15.220  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:15.221  3982  3994 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:07:15.221  3982  3982 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:07:15.222  3982  3982 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:07:15.222  3982  3982 D BtGatt.GattService: start()
,07-28 12:07:15.222  3982  3982 I bt_bluedroid: get_profile_interface gatt
,07-28 12:07:15.223  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
07-28 12:07:15.224  3982  3982 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:07:15.229  3982  3982 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:15.230  3982  3982 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:15.230  3982  3982 V BluetoothAdapterState: isBleTurningOn()=true
,07-28 12:07:15.230  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:15.230  3982  3994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-28 12:07:15.230  3982  3994 I bt_bluedroid: enable
07-28 12:07:15.231  3982  3995 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-28 12:07:15.231  3982  3995 I bt_hci  : start_up
,07-28 12:07:15.238  3982  3995 I bt_vendor: alloc value 0xb3a5f189
07-28 12:07:15.238  3982  3995 I bt_vendor: init
07-28 12:07:15.238  3982  3995 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-28 12:07:15.238  3982  3995 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-28 12:07:15.346  3982  3995 D bt_hci  : start_up starting async portion
,07-28 12:07:15.346  3982  4002 I bt_hci  : event_finish_startup
,07-28 12:07:15.347  3982  4002 I bt_hci_h4: hal_open
07-28 12:07:15.347  3982  4002 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:07:15.353  3982  4002 I bt_userial_vendor: device fd = 51 open
,07-28 12:07:15.389  3982  4002 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:07:15.421  3982  4002 D bt_hwcfg: Chipset BCM4354A2
,07-28 12:07:15.422  3982  4002 D bt_hwcfg: Target name = [BCM4354A2]
07-28 12:07:15.422  3982  4002 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-28 12:07:16.078  3982  4002 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 12:07:16.079  3982  4002 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:07:16.079  3982  4002 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:07:16.196  3982  4002 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:07:16.197  3982  4002 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-28 12:07:16.227  3982  4002 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:07:16.227  3982  4002 I bt_vendor: firmware callback
07-28 12:07:16.228  3982  4002 I bt_hci  : firmware_config_callback
,07-28 12:07:16.238  3982  4004 I bt_btu  : btu_task pending for preload complete event
,07-28 12:07:16.239  3982  4004 I bt_btu_task: Bluetooth chip preload is complete
,07-28 12:07:16.239  3982  4004 I bt_btu  : btu_task received preload complete event
,07-28 12:07:16.249  3982  4004 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:07:16.250  3982  4004 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-28 12:07:16.250  3982  4004 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:07:16.250  3982  4004 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:07:16.251  3982  4004 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:07:16.251  3982  4004 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:07:16.251  3982  4004 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-28 12:07:16.252  3982  4004 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:07:16.252  3982  4004 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:07:16.252  3982  4004 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:07:16.252  3982  4004 I         : BTE_InitTraceLevels -- TRC_SDP
,07-28 12:07:16.253  3982  4004 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:07:16.253  3982  4004 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:07:16.253  3982  4004 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:07:16.253  3982  4004 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:07:16.384  3982  4004 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39dcd9d
,07-28 12:07:16.385  3982  4004 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39dcd9d 
,07-28 12:07:16.397  3982  3998 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-28 12:07:16.399  3982  3998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-28 12:07:16.400  3982  3998 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 12:07:16.403  3982  3998 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:07:16.406  3982  3998 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:07:16.406  3982  3998 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:07:16.407  3982  3998 D bt_hci  : do_postload posting postload work item
07-28 12:07:16.407  3982  4002 I bt_hci  : event_postload
,07-28 12:07:16.407  3982  4002 I bt_vendor: sco_config_cb
07-28 12:07:16.408  3982  4002 I bt_hci  : sco_config_callback postload finished.
,07-28 12:07:16.410  3982  3998 D bt_bte_conf: Device ID record 1 : primary
,07-28 12:07:16.410  3982  3998 D bt_bte_conf:   vendorId            = 000f
07-28 12:07:16.410  3982  3998 D bt_bte_conf:   vendorIdSource      = 0001
07-28 12:07:16.410  3982  3998 D bt_bte_conf:   product             = 1200
07-28 12:07:16.411  3982  3998 D bt_bte_conf:   version             = 1436
07-28 12:07:16.411  3982  3998 D bt_bte_conf:   clientExecutableURL = 
,07-28 12:07:16.411  3982  3998 D bt_bte_conf:   serviceDescription  = 
07-28 12:07:16.411  3982  3998 D bt_bte_conf:   documentationURL    = 
07-28 12:07:16.411  3982  3998 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-28 12:07:16.412  3982  3995 D bt_stack_manager: event_start_up_stack finished
07-28 12:07:16.412  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:16.414  3982  4002 I bt_vendor: low_power_mode_cb
07-28 12:07:16.416  3982  3994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-28 12:07:16.416  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:16.416  3982  3994 D BluetoothAdapterProperties: Setting state to 15
07-28 12:07:16.417  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-28 12:07:16.418  3982  3994 I BluetoothAdapterState: Entering BleOnState
07-28 12:07:16.424  3982  3994 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-28 12:07:16.425  3982  3994 D BluetoothAdapterProperties: Setting state to 11
07-28 12:07:16.425  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-28 12:07:16.432  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
07-28 12:07:16.437  3982  3982 D HeadsetService: Received start request. Starting profile...
,07-28 12:07:16.446  3982  3994 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:07:16.448  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:16.449  3982  3982 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:07:16.450  3982  3982 D HeadsetStateMachine: make
07-28 12:07:16.452  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:16.457  3982  3982 D HeadsetStateMachine: max_hf_connections = 1
,07-28 12:07:16.458  3982  3982 I bt_bluedroid: get_profile_interface handsfree
,07-28 12:07:16.458  3982  3998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-28 12:07:16.459  3982  3998 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,07-28 12:07:16.466  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:16.467  3982  3982 D A2dpService: Received start request. Starting profile...
,07-28 12:07:16.468  3982  3982 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-28 12:07:16.469  3982  3982 I bt_bluedroid: get_profile_interface avrcp
,07-28 12:07:16.482  3982  3982 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:07:16.483  3982  3982 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:07:16.483  3982  3982 D A2dpStateMachine: make
,07-28 12:07:16.485  3982  3982 I bt_bluedroid: get_profile_interface a2dp
,07-28 12:07:16.486  3982  3998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-28 12:07:16.490  3982  4013 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:07:16.491  3982  3982 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:07:16.494  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:16.496  3758  3758 D BluetoothInputDevice: Proxy object connected
,07-28 12:07:16.496  3982  3982 D HidService: Received start request. Starting profile...
07-28 12:07:16.497  3982  3982 I bt_bluedroid: get_profile_interface hidhost
07-28 12:07:16.497  3758  3758 D HidProfile: Bluetooth service connected
07-28 12:07:16.497  3982  3998 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39be3e5
,07-28 12:07:16.498  3982  3998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-28 12:07:16.498  3982  3982 D HidService: setHidService(): set to: null
,07-28 12:07:16.500  3982  3982 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:07:16.501  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:16.501  3982  3982 D HealthService: Received start request. Starting profile...
,07-28 12:07:16.503  3982  3982 I bt_bluedroid: get_profile_interface health
,07-28 12:07:16.504  3982  3982 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:07:16.504  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:16.506  3982  3982 D PanService: Received start request. Starting profile...
,07-28 12:07:16.506  3758  3758 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:07:16.506  3982  3982 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:07:16.506  3982  3982 I bt_bluedroid: get_profile_interface pan
,07-28 12:07:16.507  3982  3998 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:07:16.508  3758  3758 D PanProfile: Bluetooth service connected
07-28 12:07:16.509  3982  3982 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:16.511  3982  3982 D BluetoothMapService: Received start request. Starting profile...
07-28 12:07:16.511  3982  3982 D BluetoothMapService: start()
07-28 12:07:16.511  3758  3758 D BluetoothMap: Proxy object connected
,07-28 12:07:16.512  3758  3758 D MapProfile: Bluetooth service connected
07-28 12:07:16.512  3758  3758 D BluetoothMap: getConnectedDevices()
07-28 12:07:16.513  3758  3758 D BluetoothMap: Bluetooth is Not enabled
07-28 12:07:16.514  3982  3982 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-28 12:07:16.514  3982  3982 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-28 12:07:16.515  3982  3982 D BluetoothMapAppObserver: createReceiver()
07-28 12:07:16.516  3982  3982 D BluetoothMapAppObserver: initObservers()
07-28 12:07:16.516  3982  3982 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-28 12:07:16.526  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:07:16.526  3982  3982 V BluetoothAdapterState: isTurningOff()=false
07-28 12:07:16.526  3982  3982 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:16.526  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:16.526  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:16.527  3982  4011 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-28 12:07:16.531  3982  3982 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:16.531  3982  3982 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:16.532  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:16.532  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:16.532  3982  3982 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:16.533  3982  3982 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:16.533  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:16.533  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:16.534  3982  3982 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:16.534  3982  3982 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:16.534  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:16.535  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:16.536  3982  3982 V BluetoothAdapterState: isTurningOff()=false
07-28 12:07:16.536  3982  3982 V BluetoothAdapterState: isTurningOn()=true
,07-28 12:07:16.536  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:16.536  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:16.537  3982  3982 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:16.537  3982  3982 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:16.537  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:16.538  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:16.538  3982  3994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,07-28 12:07:16.539  3982  3994 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:07:16.539  3982  3994 D BluetoothAdapterProperties: State =  11
,07-28 12:07:16.542  3982  3998 D BluetoothAdapterProperties: Scan Mode:21
,07-28 12:07:16.543  3982  3998 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:07:16.543  3982  3994 D BluetoothAdapterProperties: Setting state to 12
,07-28 12:07:16.543  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:07:16.544  3982  3994 I BluetoothAdapterState: Entering OnState
07-28 12:07:16.544  1360  1796 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:07:16.544  3982  3982 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-28 12:07:16.546  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:07:16.546  1360  1360 D PanProfile: Bluetooth service connected
,07-28 12:07:16.546  3758  3768 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:07:16.547  3982  3982 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,07-28 12:07:16.547  1360  3700 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:07:16.549  3982  3982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:16.550  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:16.551  3758  3770 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:07:16.552  3982  3982 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:07:16.552  3758  3768 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:07:16.553  3982  3982 D ObexServerSockets: Succeed to create listening sockets 
,07-28 12:07:16.553  3982  3982 D ObexServerSockets0: startAccept()
07-28 12:07:16.553  3982  3982 D ObexServerSockets0: prepareForNewConnect()
07-28 12:07:16.553  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:16.554  1360  1377 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:07:16.556  3982  3982 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-28 12:07:16.557  1360  1360 D BluetoothMap: Proxy object connected
07-28 12:07:16.557  1360  1360 D MapProfile: Bluetooth service connected
07-28 12:07:16.557  1360  1360 D BluetoothMap: getConnectedDevices()
07-28 12:07:16.556  3982  3982 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-28 12:07:16.557   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:16.557   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:07:16.559  3982  4019 D ObexServerSockets0: Accepting socket connection...
07-28 12:07:16.560  3982  4018 D ObexServerSockets0: Accepting socket connection...
07-28 12:07:16.561  1360  1360 D BluetoothA2dp: Proxy object connected
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:16.561  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:16.562   872   872 D BluetoothA2dp: Proxy object connected
,07-28 12:07:16.562  3758  3770 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:07:16.562  1360  3700 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:07:16.565  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:16.565  1360  1360 D BluetoothInputDevice: Proxy object connected
07-28 12:07:16.565  1360  1360 D HidProfile: Bluetooth service connected
07-28 12:07:16.566   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:16.566  1360  1377 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:07:16.567   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:16.568  1360  1796 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:16.569  1745  1972 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:16.571   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
07-28 12:07:16.572  3982  3982 D BluetoothMapService: onReceive
07-28 12:07:16.572  3982  3982 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:07:16.572  3982  3982 D BluetoothMapService: STATE_ON
07-28 12:07:16.573  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:16.575  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:16.576  3758  3758 D LocalBluetoothProfileManager: Adding local A2DP profile
,07-28 12:07:16.580  3758  3758 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-28 12:07:16.587  3758  3758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:07:16.591  3758  3758 D BluetoothA2dp: Proxy object connected
,07-28 12:07:16.593  3982  3982 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-28 12:07:16.593  3982  3982 D ObexServerSockets0: prepareForNewConnect()
,07-28 12:07:16.594  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:07:16.602  3758  3758 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:07:16.610  1360  1360 D BluetoothPbap: Proxy object connected
,07-28 12:07:16.611  1360  1360 D PbapServerProfile: Bluetooth service connected
07-28 12:07:16.611  3758  3758 D BluetoothPbap: Proxy object connected
07-28 12:07:16.611  3758  3758 D PbapServerProfile: Bluetooth service connected
,07-28 12:07:16.620  3982  4024 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:07:16.645  3982  4028 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:07:16.646  3982  4028 I BtOppRfcommListener: Accept thread started.
,07-28 12:07:16.660   872   872 D BluetoothHeadset: Proxy object connected
,07-28 12:07:16.660  1360  1796 D BluetoothHeadset: Proxy object connected
07-28 12:07:16.660   872   872 D BluetoothHeadset: Proxy object connected
07-28 12:07:16.661  1745  1860 D BluetoothHeadset: Proxy object connected
07-28 12:07:16.661  1360  1360 D HeadsetProfile: Bluetooth service connected
07-28 12:07:16.662   872   872 D BluetoothHeadset: Proxy object connected
,07-28 12:07:16.666   872   889 D BluetoothHeadset: Proxy object connected
,07-28 12:07:16.668   872   889 D BluetoothHeadset: Proxy object connected
07-28 12:07:16.668  1360  1396 D BluetoothHeadset: Proxy object connected
,07-28 12:07:16.669  1360  1360 D HeadsetProfile: Bluetooth service connected
,07-28 12:07:16.670  1745  1755 D BluetoothHeadset: Proxy object connected
,07-28 12:07:16.684  3758  3770 D BluetoothHeadset: Proxy object connected
,07-28 12:07:16.685  3758  3758 D HeadsetProfile: Bluetooth service connected
,07-28 12:07:17.989  3982  3994 D BluetoothAdapterState: Current state: ON, message: 23
,07-28 12:07:17.990  3982  3994 D BluetoothAdapterProperties: Setting state to 13
07-28 12:07:17.990  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-28 12:07:17.992  3982  3994 D BluetoothAdapterProperties: onBluetoothDisable()
,07-28 12:07:17.998  3982  3982 D BluetoothMapService: onReceive
07-28 12:07:17.998  3982  3982 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:07:17.999  3982  3982 D BluetoothMapService: STATE_TURNING_OFF
07-28 12:07:17.999  3982  3994 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:07:17.999  3982  3982 D BluetoothMapService: MAP Service closeService in
07-28 12:07:18.000  3982  3982 D BluetoothMapMasInstance0: MAP Service shutdown
07-28 12:07:18.000  3982  3998 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:07:18.000  3982  3982 D ObexServerSockets0: shutdown(block = true)
07-28 12:07:18.002  3982  4018 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-28 12:07:18.002  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:18.002  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:18.003  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:18.003  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:18.003  3982  3994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-28 12:07:18.005  3982  3982 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-28 12:07:18.005  3982  4019 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-28 12:07:18.006  3758  3758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:07:18.007  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:18.007  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:18.007  3982  4006 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-28 12:07:18.010  3701  3701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:07:18.010  3982  3982 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-28 12:07:18.010  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:18.010  3982  3982 I BtOppRfcommListener: stopping Accept Thread
07-28 12:07:18.011  3982  4028 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:07:18.012  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:18.012  3982  4028 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:07:18.014  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:18.019  3982  3982 D HeadsetService: Received stop request...Stopping profile...
,07-28 12:07:18.023  3758  3758 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:07:18.023   872   872 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:18.023  3758  3768 D BluetoothHeadset: Proxy object disconnected
,07-28 12:07:18.024  1360  1396 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:18.024   872   872 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:18.024  1745  1969 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:18.024   872   872 D BluetoothHeadset: Proxy object disconnected
07-28 12:07:18.024  3758  3758 D HeadsetProfile: Bluetooth service disconnected
,07-28 12:07:18.027  3982  3982 D A2dpService: Received stop request...Stopping profile...
07-28 12:07:18.028  1360  1360 D HeadsetProfile: Bluetooth service disconnected
07-28 12:07:18.028  3982  4013 D A2dpStateMachine: Exit Disconnected: -1
,07-28 12:07:18.031  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:07:18.031   872   872 D BluetoothA2dp: Proxy object disconnected
,07-28 12:07:18.032  1360  1360 D BluetoothA2dp: Proxy object disconnected
07-28 12:07:18.032  3982  3982 D HidService: Received stop request...Stopping profile...
07-28 12:07:18.032  3982  3982 D HidService: Stopping Bluetooth HidService
,07-28 12:07:18.034  3758  3758 D BluetoothA2dp: Proxy object disconnected
07-28 12:07:18.035  3758  3758 D BluetoothInputDevice: Proxy object disconnected
,07-28 12:07:18.035  3758  3758 D HidProfile: Bluetooth service disconnected
07-28 12:07:18.035  1360  1360 D BluetoothInputDevice: Proxy object disconnected
07-28 12:07:18.035  1360  1360 D HidProfile: Bluetooth service disconnected
07-28 12:07:18.035  3982  3982 D HealthService: Received stop request...Stopping profile...
,07-28 12:07:18.037  3982  3982 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:18.037  3982  3982 V BluetoothAdapterState: isTurningOn()=false
,07-28 12:07:18.037  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:18.037  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:18.037  3982  3982 D PanService: Received stop request...Stopping profile...
,07-28 12:07:18.038  1360  1360 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:07:18.038  1360  1360 D PanProfile: Bluetooth service disconnected
07-28 12:07:18.039  3758  3758 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:07:18.039  3758  3758 D PanProfile: Bluetooth service disconnected
,07-28 12:07:18.040  3982  3982 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:07:18.040  3982  3998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,07-28 12:07:18.040  3982  4004 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:18.040  3982  3982 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:07:18.040  3982  4004 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:18.040  3982  4004 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:18.040  3982  3998 E bt_btif : btif_hf_upstreams_evt: Invalid index 11885
,07-28 12:07:18.041  3982  3982 D BluetoothMapService: Received stop request...Stopping profile...
,07-28 12:07:18.041  3982  3982 D BluetoothMapService: stop()
07-28 12:07:18.041  3982  3982 D BluetoothMapAppObserver: deinitObservers()
,07-28 12:07:18.041  3982  3982 D BluetoothMapAppObserver: removeReceiver()
,07-28 12:07:18.043  3758  3758 D BluetoothMap: Proxy object disconnected
07-28 12:07:18.043  3758  3758 D MapProfile: Bluetooth service disconnected
07-28 12:07:18.043  1360  1360 D BluetoothMap: Proxy object disconnected
07-28 12:07:18.043  1360  1360 D MapProfile: Bluetooth service disconnected
07-28 12:07:18.044  1360  1360 D BluetoothPbap: Proxy object disconnected
,07-28 12:07:18.044  1360  1360 D PbapServerProfile: Bluetooth service disconnected
07-28 12:07:18.044  3758  3758 D BluetoothPbap: Proxy object disconnected
,07-28 12:07:18.045  3758  3758 D PbapServerProfile: Bluetooth service disconnected
07-28 12:07:18.045  3982  3982 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:18.045  3982  3982 V BluetoothAdapterState: isTurningOn()=false
,07-28 12:07:18.045  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:07:18.045  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:18.046  3982  3998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
,07-28 12:07:18.046  3982  4004 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:18.046  3982  4004 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,07-28 12:07:18.046  3982  4004 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:07:18.046  3982  4004 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:07:18.046  3982  4004 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:07:18.046  3982  4004 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:07:18.048  3982  3982 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:18.048  3982  3982 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:18.049  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:07:18.049  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:18.051  3982  3982 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:07:18.051  3982  3998 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-28 12:07:18.052  3982  3982 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:07:18.052  3982  3982 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:18.052  3982  3982 V BluetoothAdapterState: isTurningOn()=false
,07-28 12:07:18.052  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:07:18.053  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:18.053  3982  3982 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:07:18.053  3982  3998 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-28 12:07:18.053  3982  3982 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:07:18.053  3982  3982 V BluetoothAdapterState: isTurningOff()=true
,07-28 12:07:18.053  3982  3982 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:18.054  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:07:18.054  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:18.054  3982  3982 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:07:18.054  3982  3982 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 12:07:18.055  3982  3982 D BluetoothMapService: MAP Service closeService in
07-28 12:07:18.055  3982  3982 V BluetoothAdapterState: isTurningOff()=true
07-28 12:07:18.055  3982  3982 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:18.055  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:18.055  3982  3982 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:18.056  3982  3994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-28 12:07:18.056  3982  3994 D BluetoothAdapterProperties: Setting state to 15
07-28 12:07:18.056  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,07-28 12:07:18.056  3982  3994 I BluetoothAdapterState: Entering BleOnState
07-28 12:07:18.057  3982  3982 D BluetoothMapService: cleanup()
07-28 12:07:18.057  3982  3982 D BluetoothMapService: MAP Service closeService in
07-28 12:07:18.057  1360  1796 D BluetoothPan: onBluetoothStateChange on: false
,07-28 12:07:18.058  3758  3768 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:18.058  3758  3770 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:07:18.059  3758  3768 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:07:18.059  1360  1396 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:07:18.060  3758  3770 D BluetoothPan: onBluetoothStateChange on: false
07-28 12:07:18.060  3758  3768 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 12:07:18.061  1360  3700 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:07:18.061   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:18.061   872   889 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:07:18.062  3758  3770 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:07:18.062  1360  1377 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:07:18.062   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:18.062  1360  1796 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:07:18.063   872   889 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:18.063  1360  1396 D BluetoothHeadset: onBluetoothStateChange: up=false
07-28 12:07:18.063  1745  1756 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-28 12:07:18.064  3982  3994 D BluetoothAdapterState: Current state: BLE ON, message: 20
,07-28 12:07:18.064  3982  3994 D BluetoothAdapterProperties: Setting state to 16
,07-28 12:07:18.064  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-28 12:07:18.064  3982  3994 D BluetoothAdapterProperties: onBleDisable
,07-28 12:07:18.065  3982  3994 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:07:18.065  3982  3995 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,07-28 12:07:18.066  3982  3998 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:07:18.067  3982  4004 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:07:18.067  3982  4004 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-28 12:07:18.069  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes,
07-28 12:07:18.070  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:18.071  3758  3758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:07:18.072  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:18.073  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:18.075  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:07:18.083  3758  3758 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:07:18.267  3982  3998 I bt_hci  : shut_down
,07-28 12:07:18.279  3982  4002 I bt_vendor: low_power_mode_cb
07-28 12:07:18.280  3982  4002 D bt_hwcfg: hw_epilog_process
,07-28 12:07:18.296  3982  4002 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
07-28 12:07:18.296  3982  4002 I bt_vendor: epilog_cb
07-28 12:07:18.296  3982  4002 I bt_hci  : epilog_finished_callback
,07-28 12:07:18.303  3982  3998 I bt_hci_h4: hal_close
,07-28 12:07:18.305  3982  3998 I bt_userial_vendor: device fd = 51 close
,07-28 12:07:18.439  3982  3995 D bt_stack_manager: event_shut_down_stack finished.
,07-28 12:07:18.440  3982  3994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-28 12:07:18.446  3982  3982 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:07:18.447  3982  3994 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-28 12:07:18.448  3982  3982 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:07:18.448  3982  3982 D BtGatt.GattService: stop()
07-28 12:07:18.449  3982  3982 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 12:07:18.453  3982  3982 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:18.454  3982  3982 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:18.454  3982  3982 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:18.454  3982  3982 V BluetoothAdapterState: isBleTurningOff()=true
07-28 12:07:18.455  3982  3994 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-28 12:07:18.456  3982  3994 D BluetoothAdapterProperties: Setting state to 10
07-28 12:07:18.456  3982  3994 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-28 12:07:18.459  3982  3994 I BluetoothAdapterState: Entering OffState
07-28 12:07:18.460   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-28 12:07:18.483  3982  3982 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-28 12:07:18.484  3982  3982 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-28 12:07:18.484  3982  3995 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-28 12:07:18.488  3982  3982 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-28 12:07:18.497  3982  3995 D bt_stack_manager: event_clean_up_stack finished.
,07-28 12:07:18.505  3982  3982 I art     : System.exit called, status: 0
,07-28 12:07:18.505  3982  3982 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:07:18.555   872  1399 I ActivityManager: Process com.android.bluetooth (pid 3982) has died
,07-28 12:07:19.457   872  1317 D ConnectivityService: handlePromptUnvalidated 101
,07-28 12:07:20.989  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:07:20.989  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:23.997  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:07:23.997  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1692d10 added. We now have 6 listener(s)
,07-28 12:07:23.997  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:24.003  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:07:24.003  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fe34009 added. We now have 7 listener(s)
07-28 12:07:24.004  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:24.005  3701  3748 I System.out: IsBluetoothEnabled
,07-28 12:07:24.015  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:24.043   872   889 I ActivityManager: Start proc 4039:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-28 12:07:24.184  4039  4039 D AdapterServiceConfig: Adding HeadsetService
07-28 12:07:24.185  4039  4039 D AdapterServiceConfig: Adding A2dpService
07-28 12:07:24.185  4039  4039 D AdapterServiceConfig: Adding HidService
07-28 12:07:24.185  4039  4039 D AdapterServiceConfig: Adding HealthService
07-28 12:07:24.185  4039  4039 D AdapterServiceConfig: Adding PanService
07-28 12:07:24.186  4039  4039 D AdapterServiceConfig: Adding GattService
07-28 12:07:24.186  4039  4039 D AdapterServiceConfig: Adding BluetoothMapService
,07-28 12:07:24.201   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5c91be8:true
07-28 12:07:24.202  4039  4039 D BluetoothAdapterState: make() - Creating AdapterState
,07-28 12:07:24.206  4039  4039 I bt_bluedroid: init
,07-28 12:07:24.206  4039  4051 I BluetoothAdapterState: Entering OffState
,07-28 12:07:24.212  4039  4052 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-28 12:07:24.212  4039  4052 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:07:24.212  4039  4052 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-28 12:07:24.213  4039  4052 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 12:07:24.214  4039  4039 I bt_bluedroid: get_profile_interface socket
,07-28 12:07:24.216  4039  4039 I bt_bluedroid: get_profile_interface sdp
,07-28 12:07:24.225  4039  4050 I bt_bluedroid: config_hci_snoop_log
,07-28 12:07:24.225  4039  4055 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 12:07:24.230   872   889 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-28 12:07:24.235  4039  4055 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:07:24.243  4039  4051 D BluetoothAdapterState: Current state: OFF, message: 0
,07-28 12:07:24.244  4039  4051 D BluetoothAdapterProperties: Setting state to 14
,07-28 12:07:24.244  4039  4051 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-28 12:07:24.247  4039  4051 D BluetoothBondStateMachine: make
,07-28 12:07:24.253  4039  4056 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:07:24.257  4039  4051 I BluetoothAdapterState: Entering PendingCommandState
,07-28 12:07:24.260  4039  4039 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-28 12:07:24.263  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:24.264  4039  4039 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:07:24.265  4039  4039 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:07:24.265  4039  4039 D BtGatt.GattService: start()
,07-28 12:07:24.265  4039  4039 I bt_bluedroid: get_profile_interface gatt
,07-28 12:07:24.266  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
07-28 12:07:24.266  4039  4039 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:07:24.274  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:24.274  4039  4039 V BluetoothAdapterState: isTurningOn()=false
07-28 12:07:24.274  4039  4039 V BluetoothAdapterState: isBleTurningOn()=true
,07-28 12:07:24.274  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:24.275  4039  4051 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,07-28 12:07:24.275  4039  4051 I bt_bluedroid: enable
07-28 12:07:24.275  4039  4052 D bt_stack_manager: event_start_up_stack is bringing up the stack.
07-28 12:07:24.275  4039  4052 I bt_hci  : start_up
,07-28 12:07:24.288  4039  4052 I bt_vendor: alloc value 0xb3a5f189
,07-28 12:07:24.288  4039  4052 I bt_vendor: init
,07-28 12:07:24.288  4039  4052 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:07:24.288  4039  4052 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-28 12:07:24.392  4039  4052 D bt_hci  : start_up starting async portion
,07-28 12:07:24.393  4039  4059 I bt_hci  : event_finish_startup
,07-28 12:07:24.393  4039  4059 I bt_hci_h4: hal_open
07-28 12:07:24.393  4039  4059 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:07:24.396  4039  4059 I bt_userial_vendor: device fd = 51 open
,07-28 12:07:24.436  4039  4059 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:07:24.468  4039  4059 D bt_hwcfg: Chipset BCM4354A2
,07-28 12:07:24.468  4039  4059 D bt_hwcfg: Target name = [BCM4354A2]
07-28 12:07:24.468  4039  4059 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-28 12:07:25.125  4039  4059 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 12:07:25.126  4039  4059 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:07:25.126  4039  4059 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:07:25.243  4039  4059 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:07:25.244  4039  4059 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-28 12:07:25.274  4039  4059 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:07:25.274  4039  4059 I bt_vendor: firmware callback
07-28 12:07:25.274  4039  4059 I bt_hci  : firmware_config_callback
,07-28 12:07:25.287  4039  4061 I bt_btu  : btu_task pending for preload complete event
,07-28 12:07:25.287  4039  4061 I bt_btu_task: Bluetooth chip preload is complete
,07-28 12:07:25.288  4039  4061 I bt_btu  : btu_task received preload complete event
,07-28 12:07:25.297  4039  4061 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:07:25.297  4039  4061 I         : BTE_InitTraceLevels -- TRC_L2CAP
,07-28 12:07:25.298  4039  4061 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,07-28 12:07:25.298  4039  4061 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:07:25.298  4039  4061 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:07:25.299  4039  4061 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:07:25.299  4039  4061 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-28 12:07:25.299  4039  4061 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:07:25.299  4039  4061 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:07:25.300  4039  4061 I         : BTE_InitTraceLevels -- TRC_PAN
,07-28 12:07:25.300  4039  4061 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:07:25.300  4039  4061 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:07:25.300  4039  4061 I         : BTE_InitTraceLevels -- TRC_SMP
,07-28 12:07:25.301  4039  4061 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:07:25.301  4039  4061 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:07:25.433  4039  4061 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb39dcd9d
,07-28 12:07:25.434  4039  4061 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb39dcd9d 
,07-28 12:07:25.452  4039  4055 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-28 12:07:25.454  4039  4055 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-28 12:07:25.455  4039  4055 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-28 12:07:25.460  4039  4055 D BluetoothAdapterProperties: Name is: Nexus 6
,07-28 12:07:25.465  4039  4055 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:07:25.466  4039  4055 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:07:25.467  4039  4055 D bt_hci  : do_postload posting postload work item
07-28 12:07:25.468  4039  4059 I bt_hci  : event_postload
,07-28 12:07:25.468  4039  4059 I bt_vendor: sco_config_cb
,07-28 12:07:25.468  4039  4059 I bt_hci  : sco_config_callback postload finished.
07-28 12:07:25.470  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:25.473  4039  4055 D bt_bte_conf: Device ID record 1 : primary
07-28 12:07:25.473  4039  4055 D bt_bte_conf:   vendorId            = 000f
07-28 12:07:25.473  4039  4055 D bt_bte_conf:   vendorIdSource      = 0001
07-28 12:07:25.474  4039  4055 D bt_bte_conf:   product             = 1200
07-28 12:07:25.474  4039  4055 D bt_bte_conf:   version             = 1436
07-28 12:07:25.474  4039  4055 D bt_bte_conf:   clientExecutableURL = 
07-28 12:07:25.474  4039  4055 D bt_bte_conf:   serviceDescription  = 
07-28 12:07:25.474  4039  4055 D bt_bte_conf:   documentationURL    = 
07-28 12:07:25.475  4039  4059 I bt_vendor: low_power_mode_cb
07-28 12:07:25.475  4039  4055 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-28 12:07:25.475  4039  4052 D bt_stack_manager: event_start_up_stack finished
07-28 12:07:25.477  4039  4051 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-28 12:07:25.478  4039  4051 D BluetoothAdapterProperties: Setting state to 15
07-28 12:07:25.478  4039  4051 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-28 12:07:25.480  4039  4051 I BluetoothAdapterState: Entering BleOnState
,07-28 12:07:25.485  4039  4051 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-28 12:07:25.486  4039  4051 D BluetoothAdapterProperties: Setting state to 11
,07-28 12:07:25.486  4039  4051 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-28 12:07:25.491  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:25.491  4039  4039 D HeadsetService: Received start request. Starting profile...
07-28 12:07:25.494  4039  4039 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-28 12:07:25.495  4039  4039 D HeadsetStateMachine: make
,07-28 12:07:25.502  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:25.510  4039  4039 D HeadsetStateMachine: max_hf_connections = 1
,07-28 12:07:25.510  4039  4039 I bt_bluedroid: get_profile_interface handsfree
07-28 12:07:25.510  4039  4055 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,07-28 12:07:25.511  4039  4055 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-28 12:07:25.515  4039  4051 I BluetoothAdapterState: Entering PendingCommandState
07-28 12:07:25.515  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:25.516  4039  4039 D A2dpService: Received start request. Starting profile...
,07-28 12:07:25.517  4039  4039 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-28 12:07:25.517  4039  4039 I bt_bluedroid: get_profile_interface avrcp
,07-28 12:07:25.524  4039  4039 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
07-28 12:07:25.524  4039  4039 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:07:25.524  4039  4039 D A2dpStateMachine: make
,07-28 12:07:25.526  4039  4039 I bt_bluedroid: get_profile_interface a2dp
07-28 12:07:25.527  4039  4055 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
07-28 12:07:25.528  4039  4069 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:07:25.530  4039  4039 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:07:25.531  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
07-28 12:07:25.532  4039  4039 D HidService: Received start request. Starting profile...
,07-28 12:07:25.532  4039  4039 I bt_bluedroid: get_profile_interface hidhost
,07-28 12:07:25.532  4039  4039 D HidService: setHidService(): set to: null
07-28 12:07:25.533  4039  4055 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39be3e5
07-28 12:07:25.533  4039  4055 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,07-28 12:07:25.533  4039  4039 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:07:25.534  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
07-28 12:07:25.535  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-28 12:07:25.535  4039  4039 D HealthService: Received start request. Starting profile...
,07-28 12:07:25.537  4039  4039 I bt_bluedroid: get_profile_interface health
,07-28 12:07:25.538  4039  4039 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:07:25.538  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
07-28 12:07:25.539  4039  4039 D PanService: Received start request. Starting profile...
07-28 12:07:25.539  4039  4039 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:07:25.539  4039  4039 I bt_bluedroid: get_profile_interface pan
,07-28 12:07:25.540  4039  4055 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
07-28 12:07:25.541  4039  4039 V BluetoothAdapterState: isTurningOff()=false
07-28 12:07:25.541  4039  4039 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:25.541  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:25.541  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
07-28 12:07:25.544  4039  4067 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:07:25.545  4039  4039 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:25.545  4039  4039 D BluetoothMapService: Received start request. Starting profile...
07-28 12:07:25.546  4039  4039 D BluetoothMapService: start()
,07-28 12:07:25.550  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-28 12:07:25.551  4039  4039 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,07-28 12:07:25.551  4039  4039 D BluetoothMapAppObserver: createReceiver()
,07-28 12:07:25.555  4039  4039 D BluetoothMapAppObserver: initObservers()
,07-28 12:07:25.555  4039  4039 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isTurningOff()=false
07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
,07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:25.562  4039  4039 V BluetoothAdapterState: isTurningOff()=false
,07-28 12:07:25.563  4039  4039 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:25.563  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:25.563  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:25.565  4039  4039 V BluetoothAdapterState: isTurningOff()=false
07-28 12:07:25.565  4039  4039 V BluetoothAdapterState: isTurningOn()=true
07-28 12:07:25.565  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:25.566  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:25.566  4039  4039 V BluetoothAdapterState: isTurningOff()=false
07-28 12:07:25.566  4039  4039 V BluetoothAdapterState: isTurningOn()=true
,07-28 12:07:25.566  4039  4039 V BluetoothAdapterState: isBleTurningOn()=false
07-28 12:07:25.566  4039  4039 V BluetoothAdapterState: isBleTurningOff()=false
,07-28 12:07:25.566  4039  4051 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-28 12:07:25.566  4039  4051 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:07:25.566  4039  4051 D BluetoothAdapterProperties: State =  11
07-28 12:07:25.567  4039  4051 D BluetoothAdapterProperties: Setting state to 12
07-28 12:07:25.567  4039  4051 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-28 12:07:25.568  4039  4051 I BluetoothAdapterState: Entering OnState
07-28 12:07:25.569  1360  1796 D BluetoothPan: onBluetoothStateChange on: true
,07-28 12:07:25.570  4039  4055 D BluetoothAdapterProperties: Scan Mode:21
07-28 12:07:25.570  4039  4055 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:07:25.575  3758  4032 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:25.576  1360  1360 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:07:25.576  1360  1360 D PanProfile: Bluetooth service connected
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:25.577  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:07:25.577  3758  3770 D BluetoothMap: onBluetoothStateChange: up=true
07-28 12:07:25.580  3758  3768 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:07:25.581  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:25.581  3758  3758 D BluetoothMap: Proxy object connected
07-28 12:07:25.582  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-28 12:07:25.581  3758  3758 D MapProfile: Bluetooth service connected
07-28 12:07:25.582  3758  3758 D BluetoothMap: getConnectedDevices()
07-28 12:07:25.583  4039  4039 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-28 12:07:25.583  1360  3700 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:07:25.584  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:07:25.585  3758  4032 D BluetoothPan: onBluetoothStateChange on: true
07-28 12:07:25.587  4039  4039 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:07:25.588  3758  3768 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:07:25.589  4039  4039 D ObexServerSockets: Succeed to create listening sockets 
07-28 12:07:25.590  4039  4039 D ObexServerSockets0: startAccept()
,07-28 12:07:25.590  4039  4039 D ObexServerSockets0: prepareForNewConnect()
,07-28 12:07:25.590  1360  1377 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:07:25.590  3758  3758 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 12:07:25.591  3758  3758 D PanProfile: Bluetooth service connected
07-28 12:07:25.592   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:07:25.592   872   889 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:07:25.592  1360  1360 D BluetoothMap: Proxy object connected
07-28 12:07:25.592  1360  1360 D MapProfile: Bluetooth service connected
07-28 12:07:25.592  1360  1360 D BluetoothMap: getConnectedDevices()
07-28 12:07:25.593  4039  4039 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-28 12:07:25.593  4039  4039 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-28 12:07:25.593  3758  3770 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:07:25.595   872   872 D BluetoothA2dp: Proxy object connected
07-28 12:07:25.595  1360  1360 D BluetoothA2dp: Proxy object connected
07-28 12:07:25.595  4039  4076 D ObexServerSockets0: Accepting socket connection...
07-28 12:07:25.596  1360  3700 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:07:25.598  4039  4077 D ObexServerSockets0: Accepting socket connection...
07-28 12:07:25.598   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:25.599  1360  1396 D BluetoothPbap: onBluetoothStateChange: up=true
07-28 12:07:25.599  1360  1360 D BluetoothInputDevice: Proxy object connected
07-28 12:07:25.599  1360  1360 D HidProfile: Bluetooth service connected
,07-28 12:07:25.601   872   889 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:25.601  1360  1377 D BluetoothHeadset: onBluetoothStateChange: up=true
07-28 12:07:25.602  3758  3758 D BluetoothA2dp: Proxy object connected
07-28 12:07:25.602  1745  1969 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-28 12:07:25.606   872   872 I Telecom : BluetoothPhoneService: queryPhoneState
,07-28 12:07:25.607  3758  3758 D BluetoothInputDevice: Proxy object connected
07-28 12:07:25.607  3758  3758 D HidProfile: Bluetooth service connected
,07-28 12:07:25.610  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:25.610  4039  4039 D BluetoothMapService: onReceive
07-28 12:07:25.610  4039  4039 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:07:25.610  4039  4039 D BluetoothMapService: STATE_ON
,07-28 12:07:25.617  3758  3758 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:07:25.625  3758  3758 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:07:25.626  1527  1527 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-28 12:07:25.644  3758  3758 D BluetoothPbap: Proxy object connected
,07-28 12:07:25.644  3758  3758 D PbapServerProfile: Bluetooth service connected
07-28 12:07:25.644  4039  4039 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-28 12:07:25.644  1360  1360 D BluetoothPbap: Proxy object connected
07-28 12:07:25.644  4039  4039 D ObexServerSockets0: prepareForNewConnect()
07-28 12:07:25.644  1360  1360 D PbapServerProfile: Bluetooth service connected
,07-28 12:07:25.658  4039  4082 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:07:25.672  4039  4086 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:07:25.674  4039  4086 I BtOppRfcommListener: Accept thread started.
,07-28 12:07:25.677   872   872 D BluetoothHeadset: Proxy object connected
,07-28 12:07:25.678  3758  4032 D BluetoothHeadset: Proxy object connected
,07-28 12:07:25.678  3758  3758 D HeadsetProfile: Bluetooth service connected
,07-28 12:07:25.679  1360  1377 D BluetoothHeadset: Proxy object connected
,07-28 12:07:25.679   872   872 D BluetoothHeadset: Proxy object connected
07-28 12:07:25.679  1360  1360 D HeadsetProfile: Bluetooth service connected
07-28 12:07:25.680  1745  1756 D BluetoothHeadset: Proxy object connected
07-28 12:07:25.680   872   872 D BluetoothHeadset: Proxy object connected
,07-28 12:07:25.692   872   889 D BluetoothHeadset: Proxy object connected
,07-28 12:07:25.699   872   889 D BluetoothHeadset: Proxy object connected
,07-28 12:07:25.701   872   889 D BluetoothHeadset: Proxy object connected
,07-28 12:07:25.702  1360  3700 D BluetoothHeadset: Proxy object connected
07-28 12:07:25.702  1360  1360 D HeadsetProfile: Bluetooth service connected
,07-28 12:07:25.704  1745  1972 D BluetoothHeadset: Proxy object connected
,07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:26.036  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:26.043  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:26.046  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:07:26.047  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13b320e added. We now have 8 listener(s)
,07-28 12:07:26.047  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:26.053   872  3091 D WifiService: setWifiEnabled: false pid=3701, uid=10000
,07-28 12:07:26.053   872  3091 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:07:26.065  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:26.066   872  1764 D WifiService: setWifiEnabled: true pid=3701, uid=10000
,07-28 12:07:26.067   872  1764 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-28 12:07:26.079   872  1315 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:26.096  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:26.105  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:26.116   872  1315 D WifiConfigStore: loaded 0 passpoint configs
,07-28 12:07:26.116   872  1315 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:07:26.116   872  1315 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
07-28 12:07:26.117   872  1315 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-28 12:07:26.118   872  1315 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-28 12:07:26.118   872  1315 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-28 12:07:26.118   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-28 12:07:26.119   872  1315 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-28 12:07:26.135   372   870 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
07-28 12:07:26.135   872  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:07:26.137   372   870 D CommandListener: Setting iface cfg
,07-28 12:07:26.188   872  1314 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
,07-28 12:07:26.188   872  1314 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:07:26.194   872  1315 E native  : do suspend true
,07-28 12:07:26.213   872  1314 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:07:26.224   872  1314 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-28 12:07:26.228   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:27.091  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:27.098  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:27.117  3701  3748 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-28 12:07:27.120  3701  3748 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-28 12:07:27.129  3701  3748 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a829625 Bundle[{}]
,07-28 12:07:27.131  3701  3748 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:07:27.132  3701  3748 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-28 12:07:27.134  3701  3748 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-28 12:07:27.137  3701  3748 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-28 12:07:27.137  3701  3748 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-28 12:07:27.138  3701  3748 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-28 12:07:27.143  3701  3748 I System.out: Running OutgoingSocketThread
07-28 12:07:27.145  3701  4092 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 416)
,07-28 12:07:27.146  3701  4092 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 40142
07-28 12:07:27.147  3701  4092 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-28 12:07:27.639   872  1315 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-28 12:07:27.775   872  1315 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=9.25 rxSuccessRate=13.69 delta 1000 -> 994
,07-28 12:07:27.776   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-28 12:07:27.776   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:07:27.794   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-28 12:07:27.850   872  1315 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-28 12:07:27.852  1474  1474 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-28 12:07:28.146  3701  3748 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 417)
,07-28 12:07:28.147  3701  3748 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 417)
07-28 12:07:28.147  3701  3748 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 417)
,07-28 12:07:28.147  3701  3748 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 417)
,07-28 12:07:28.157  3701  3748 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 422)
,07-28 12:07:28.157  3701  3748 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 422)
,07-28 12:07:28.158  3701  3748 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 422)
,07-28 12:07:28.161  3701  3748 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 423)
,07-28 12:07:28.164  3701  3748 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 425)
,07-28 12:07:28.166  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:07:28.166  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@448c42f added. We now have 2 listener(s)
,07-28 12:07:28.168  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:07:28.168  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.168  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:28.168  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.168  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1c0a3c added. We now have 9 listener(s)
07-28 12:07:28.168  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:28.169  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:07:28.172  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:28.177  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:28.179  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:28.180  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:28.181  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:07:28.181  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97c611a added. We now have 3 listener(s)
,07-28 12:07:28.183  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:28.184  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:28.188  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:07:28.188  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:07:28.189  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:28.189  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.190  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7744b added. We now have 10 listener(s)
07-28 12:07:28.190  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:28.190  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:28.191  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:28.191  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:28.191  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:28.191  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.191  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:28.192  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.192  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@448c42f removed from the list
07-28 12:07:28.192  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.192  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1c0a3c removed from the list
07-28 12:07:28.192  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:28.193  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.193  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.193  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:28.195  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:28.195  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.196  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:07:28.196  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1c0a3c not in the list
07-28 12:07:28.196  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:28.196  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:28.198  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.199  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:28.199  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.199  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7744b removed from the list
,07-28 12:07:28.199  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:28.200  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.200  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:28.200  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.200  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@97c611a removed from the list
,07-28 12:07:28.202  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:07:28.203  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd8e28 added. We now have 2 listener(s)
,07-28 12:07:28.208  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:07:28.209  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.209  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:07:28.210  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.210  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf5e741 added. We now have 9 listener(s)
,07-28 12:07:28.210  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:28.211  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported,
,07-28 12:07:28.214  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:28.219  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:28.221  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:28.221  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:28.222  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:07:28.222  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af70a27 added. We now have 3 listener(s)
07-28 12:07:28.223  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:28.224  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:07:28.224  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.224  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:28.224  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:28.225  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.225  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17164d4 added. We now have 10 listener(s)
07-28 12:07:28.225  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:28.225  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:07:28.225  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:07:28.225  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:28.225  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:07:28.228  3701  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-28 12:07:28.228  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:07:28.233  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:07:28.234  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-28 12:07:28.234  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:07:28.238  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:07:28.238  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-28 12:07:28.238  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-28 12:07:28.239  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:28.244  4039  4050 D BtGatt.GattService: registerClient() - UUID=df3921af-b95c-44d1-84ec-36f957935532
,07-28 12:07:28.246  4039  4055 D BtGatt.GattService: onClientRegistered() - UUID=df3921af-b95c-44d1-84ec-36f957935532, clientIf=5
,07-28 12:07:28.247  3701  3711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:07:28.248  4039  4078 D BtGatt.GattService: start scan with filters
,07-28 12:07:28.252  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-28 12:07:28.252  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:07:28.252  4039  4058 D BtGatt.ScanManager: handling starting scan
,07-28 12:07:28.252  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:07:28.253  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 12:07:28.255  4039  4058 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@7b59c69
,07-28 12:07:28.259  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:07:28.259  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-28 12:07:28.259  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:07:28.260  4039  4055 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-28 12:07:28.260  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:28.261  4039  4058 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-28 12:07:28.261  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 12:07:28.264  3701  3748 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-28 12:07:28.264  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:07:28.264  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:28.265  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,07-28 12:07:28.265  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:07:28.265  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-28 12:07:28.265  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:07:28.265  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-28 12:07:28.265  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-28 12:07:28.265  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 12:07:28.266  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:28.267  4039  4078 D BtGatt.GattService: stopScan() - queue size =1
,07-28 12:07:28.268  4039  4049 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-28 12:07:28.268  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-28 12:07:28.269  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-28 12:07:28.269  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-28 12:07:28.269  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
,07-28 12:07:28.269  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 12:07:28.271  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 12:07:28.271  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-28 12:07:28.271  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-28 12:07:28.271  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:07:28.272  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:07:28.273  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-28 12:07:28.273  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:28.274  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:28.275  4039  4055 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:07:28.275  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.276  4039  4058 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:07:28.276  4039  4058 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-28 12:07:28.276  1474  1474 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-28 12:07:28.277  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:28.278  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:28.278  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:28.278  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:28.278  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.278  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:28.278  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.278  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@bd8e28 removed from the list
07-28 12:07:28.279  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:07:28.279  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf5e741 removed from the list
07-28 12:07:28.279  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:28.279  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.279  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.280  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:28.281  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:28.281  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.281  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.281  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cf5e741 not in the list
07-28 12:07:28.281  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:28.281  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.283  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.283  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:28.283  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:07:28.283  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17164d4 removed from the list
07-28 12:07:28.283  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:28.284  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.284  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.284  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.285  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@af70a27 removed from the list
07-28 12:07:28.286  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:07:28.286  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e9fa40 added. We now have 2 listener(s)
07-28 12:07:28.289  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-28 12:07:28.289  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.289  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:28.289  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.289  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5f3d79 added. We now have 9 listener(s)
07-28 12:07:28.290  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:28.290  4039  4055 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:07:28.290  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.290  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:07:28.294  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:28.300  4039  4055 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-28 12:07:28.300  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:28.301  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:28.303  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:07:28.303  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:28.303  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:07:28.304  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@579171f added. We now have 3 listener(s)
07-28 12:07:28.305  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:28.305  1474  1474 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:07:28.305  1474  1474 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
07-28 12:07:28.306  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:28.308  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:07:28.308  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.309  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:28.309  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.309  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a947a6c added. We now have 10 listener(s)
,07-28 12:07:28.309  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:28.309  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:07:28.310  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:07:28.310  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:07:28.310  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:28.310  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:07:28.311   872  1315 D WifiConfigStore: Retrieve network priorities after PNO.
,07-28 12:07:28.313  3701  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:07:28.313  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:07:28.317  4039  4055 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:07:28.317  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.317  4039  4058 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:07:28.319  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:07:28.319  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:07:28.320  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:07:28.323   872  1315 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:07:28.324   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-28 12:07:28.324   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:07:28.325  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-28 12:07:28.325  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-28 12:07:28.325  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:07:28.327  4039  4055 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:07:28.327  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.327  3701  3748 D BluetoothAdapter: STATE_ON
07-28 12:07:28.327  4039  4058 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-28 12:07:28.329  4039  4050 D BtGatt.GattService: registerClient() - UUID=ff82e288-65b5-4a69-9c30-d5eeb35d07de
07-28 12:07:28.329  4039  4055 D BtGatt.GattService: onClientRegistered() - UUID=ff82e288-65b5-4a69-9c30-d5eeb35d07de, clientIf=5
,07-28 12:07:28.330  3701  3711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:07:28.330  4039  4049 D BtGatt.GattService: start scan with filters
,07-28 12:07:28.333  4039  4055 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:07:28.333  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.334   872  1315 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any,
07-28 12:07:28.334  4039  4058 D BtGatt.ScanManager: handling starting scan
,07-28 12:07:28.335  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-28 12:07:28.335  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-28 12:07:28.335  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:07:28.335  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-28 12:07:28.340  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:07:28.342  4039  4055 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-28 12:07:28.342  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.342  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-28 12:07:28.342  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-28 12:07:28.342  4039  4058 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-28 12:07:28.343   372   870 D CommandListener: Setting iface cfg
07-28 12:07:28.344  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-28 12:07:28.346  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:07:28.346  3701  3748 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,07-28 12:07:28.346  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:07:28.346  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:07:28.346  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:28.346  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:28.346  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:28.347  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 12:07:28.347  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.347  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e9fa40 removed from the list
07-28 12:07:28.347   872  1315 D WifiStateMachine: Start Dhcp Watchdog 3
07-28 12:07:28.347  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.347  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5f3d79 removed from the list
,07-28 12:07:28.347  4039  4055 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:07:28.347  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:28.347  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.347  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:28.347  4039  4058 D BtGatt.ScanManager: Starting BLE batch scan
,07-28 12:07:28.347  4039  4058 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:07:28.347  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.347  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-28 12:07:28.347  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.347  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:07:28.348  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:28.348  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.348  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.348  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f5f3d79 not in the list
07-28 12:07:28.348  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:07:28.348  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:07:28.349  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:07:28.349  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:07:28.349  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-28 12:07:28.349  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:28.350  4039  4075 D BtGatt.GattService: stopScan() - queue size =1
,07-28 12:07:28.350  4039  4078 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:07:28.350  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:07:28.351  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-28 12:07:28.351  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:07:28.351  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 12:07:28.351  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-28 12:07:28.352  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 12:07:28.352  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 12:07:28.352  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:07:28.352  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:07:28.353   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
07-28 12:07:28.353  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.353  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:07:28.354  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:28.354  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.354  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:28.354  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a947a6c removed from the list
07-28 12:07:28.354  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:28.354  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:28.354  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.354  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:28.354  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:28.354  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.354  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@579171f removed from the list
07-28 12:07:28.354  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:07:28.355  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@984d158 added. We now have 2 listener(s)
07-28 12:07:28.356  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:07:28.356  4039  4055 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:07:28.356  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:28.357  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.357  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:28.357  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.357  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76622b1 added. We now have 9 listener(s)
,07-28 12:07:28.357  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:28.357  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:07:28.359  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:28.361  4039  4055 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-28 12:07:28.361  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:28.362  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:28.363   872  4095 D DhcpClient: Receive thread started
,07-28 12:07:28.364  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:28.364  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:28.364  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:07:28.364  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a0cb17 added. We now have 3 listener(s)
,07-28 12:07:28.366  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:28.367  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:07:28.367  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.367  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:07:28.367  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:07:28.367  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@421ab04 added. We now have 10 listener(s)
,07-28 12:07:28.367  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:07:28.367  4039  4055 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:07:28.367  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:28.368  4039  4058 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:07:28.368  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:28.368  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:07:28.368  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:07:28.368  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:07:28.368  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:07:28.370  3701  3748 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-28 12:07:28.370  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:07:28.373  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:07:28.373  4039  4055 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:07:28.373  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.373  4039  4058 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 12:07:28.374  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-28 12:07:28.374  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:07:28.376  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-28 12:07:28.376  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,07-28 12:07:28.377  3701  3748 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-28 12:07:28.377  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:28.378  4039  4055 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-28 12:07:28.378  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:28.379  4039  4049 D BtGatt.GattService: registerClient() - UUID=0c6baf0f-64bf-445c-a7ff-203b54d296ec
07-28 12:07:28.379  4039  4055 D BtGatt.GattService: onClientRegistered() - UUID=0c6baf0f-64bf-445c-a7ff-203b54d296ec, clientIf=5
07-28 12:07:28.379  3701  3711 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-28 12:07:28.379  4039  4075 D BtGatt.GattService: start scan with filters
,07-28 12:07:28.381  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-28 12:07:28.381  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-28 12:07:28.381  4039  4058 D BtGatt.ScanManager: handling starting scan
07-28 12:07:28.381  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-28 12:07:28.381  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-28 12:07:28.384  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:07:28.384  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-28 12:07:28.384  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-28 12:07:28.386  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-28 12:07:28.386  4039  4055 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-28 12:07:28.386  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.386  4039  4058 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-28 12:07:28.389  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:07:28.389  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:07:28.389  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:28.390  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:28.390  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:07:28.390  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-28 12:07:28.390  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.390  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@984d158 removed from the list
07-28 12:07:28.390  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.390  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76622b1 removed from the list
07-28 12:07:28.390  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:28.390  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:07:28.391  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.391  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-28 12:07:28.391  4039  4055 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-28 12:07:28.391  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.391  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-28 12:07:28.391  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:28.391  4039  4058 D BtGatt.ScanManager: Starting BLE batch scan
07-28 12:07:28.391  4039  4058 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-28 12:07:28.392  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:28.392  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:07:28.392  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.392  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@76622b1 not in the list
07-28 12:07:28.392  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:07:28.392  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-28 12:07:28.392  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:07:28.392  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:07:28.392  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-28 12:07:28.393  3701  3748 D BluetoothAdapter: STATE_ON
,07-28 12:07:28.393  4039  4074 D BtGatt.GattService: stopScan() - queue size =1
07-28 12:07:28.394  4039  4049 D BtGatt.GattService: unregisterClient() - clientIf=5
07-28 12:07:28.394  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:07:28.394  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-28 12:07:28.394  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-28 12:07:28.394  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-28 12:07:28.395  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-28 12:07:28.395  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:07:28.396  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-28 12:07:28.396  3701  3748 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-28 12:07:28.396  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:07:28.396  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:28.397  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.397  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:28.397  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.397  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:28.397  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@421ab04 removed from the list
07-28 12:07:28.397  3701  3701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:07:28.397  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:28.397  3701  3701 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 12:07:28.397  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.397  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.397  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.397  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a0cb17 removed from the list
07-28 12:07:28.398  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:07:28.398  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a907370 added. We now have 2 listener(s)
,07-28 12:07:28.399  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:07:28.400  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.400  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:07:28.400  4039  4055 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-28 12:07:28.400  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.400  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.400  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4d76e9 added. We now have 9 listener(s)
,07-28 12:07:28.400  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:28.401  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:07:28.402  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:07:28.405  4039  4055 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-28 12:07:28.405  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:07:28.405  3701  3748 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:07:28.407  3701  3748 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:07:28.407  3701  3748 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:07:28.407  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:07:28.407  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19c060f added. We now have 3 listener(s)
,07-28 12:07:28.408  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:07:28.408  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-28 12:07:28.408  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:07:28.408  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:07:28.409  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:07:28.409  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:07:28.409  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e1569c added. We now have 10 listener(s)
07-28 12:07:28.409  3701  3748 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:07:28.409  3701  3748 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-28 12:07:28.409  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:07:28.409  3701  3748 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:07:28.409  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:07:28.409  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.409  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:07:28.410  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.410  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a907370 removed from the list
07-28 12:07:28.410  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:07:28.410  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4d76e9 removed from the list
07-28 12:07:28.410  3701  3748 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:07:28.410  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.410  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.410  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.411  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:07:28.411  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.411  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.411  3701  3748 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b4d76e9 not in the list
07-28 12:07:28.411  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.411  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:07:28.412  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:07:28.412  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:07:28.412  3701  3748 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:07:28.412  3701  3748 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7e1569c removed from the list
07-28 12:07:28.412  3701  3748 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:07:28.412  3701  3748 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:07:28.412  3701  3748 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:07:28.412  3701  3748 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:07:28.413  3701  3748 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@19c060f removed from the list
,07-28 12:07:28.413  4039  4055 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-28 12:07:28.413  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.413  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:07:28.413  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:07:28.413  4039  4058 D BtGatt.ScanManager: stopping BLe Batch
07-28 12:07:28.414  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-28 12:07:28.414  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:07:28.414  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:07:28.414  3701  3748 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:07:28.419  3701  4096 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 431, name: My test thread name)
,07-28 12:07:28.419  3701  4096 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 431, thread name: My test thread name)
,07-28 12:07:28.419  3701  4096 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 431, name: My test thread name)
07-28 12:07:28.419  4039  4055 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-28 12:07:28.419  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.419  4039  4058 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-28 12:07:28.421  3701  4097 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 433, name: My test thread name)
,07-28 12:07:28.421  3701  4097 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 433, thread name: My test thread name)
07-28 12:07:28.421  3701  4097 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 433, name: My test thread name)
,07-28 12:07:28.423  3701  3748 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 12:07:28.423  3701  3748 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 12:07:28.423  3701  3748 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:07:28.423  3701  3748 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,07-28 12:07:28.423  3701  3748 D com.test.thalitest.ThaliTestRunner: Total duration: 22861 ms
,07-28 12:07:28.425  3701  3748 I jxcore-log: Total number of executed tests:  80
07-28 12:07:28.425  3701  3748 I jxcore-log: 
,07-28 12:07:28.425  3701  3748 I jxcore-log: Number of passed tests:  80
07-28 12:07:28.425  3701  3748 I jxcore-log: 
07-28 12:07:28.425  3701  3748 I jxcore-log: Number of failed tests:  0
07-28 12:07:28.425  3701  3748 I jxcore-log: 
07-28 12:07:28.426  3701  3748 I jxcore-log: Number of ignored tests:  0
07-28 12:07:28.426  3701  3748 I jxcore-log: 
07-28 12:07:28.426  3701  3748 I jxcore-log: Total duration:  22861
07-28 12:07:28.426  3701  3748 I jxcore-log: 
07-28 12:07:28.426  3701  3748 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:07:28.426  3701  3748 I jxcore-log: 
,07-28 12:07:28.430  4039  4055 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
07-28 12:07:28.430  4039  4055 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-28 12:07:28.430  4039  4055 D BtGatt.GattService: current time is 305164762961
07-28 12:07:28.430  4039  4055 D BtGatt.GattService: Batch record : [107, 58, 19, -9, 93, -60, 1, 0, -103, 0, 0, 30, 14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 27, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
07-28 12:07:28.431  4039  4055 D BtGatt.GattService: ScanRecord : [14, 9, 66, 114, 97, 99, 101, 108, 105, 53, 45, 52, 57, 53, 53, 2, 1, 5, 11, -1, -25, -2, 0, 1, -60, 93, -9, 19, 58, 107, 2, 10, 0, 5, 3, 32, -1, -25, -2, 17, 7, -48, 0, 45, 18, 30, 75, 15, -92, -103, 78, -50, -75, 49, -12, 5, 121]
07-28 12:07:28.435  3701  3701 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 12:07:28.435  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.435  3701  3748 I jxcore-log: 
07-28 12:07:28.438  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.438  3701  3748 I jxcore-log: 
07-28 12:07:28.438  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.438  3701  3748 I jxcore-log: 
07-28 12:07:28.439  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 12:07:28.439  3701  3748 I jxcore-log: 
07-28 12:07:28.440  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:07:28.440  3701  3748 I jxcore-log: 
07-28 12:07:28.441  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.441  3701  3748 I jxcore-log: 
07-28 12:07:28.443  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 12:07:28.443  3701  3748 I jxcore-log: 
07-28 12:07:28.444  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:07:28.444  3701  3748 I jxcore-log: 
,07-28 12:07:28.445  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.445  3701  3748 I jxcore-log: 
,07-28 12:07:28.445   872  1315 E native  : do suspend false
07-28 12:07:28.446  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 12:07:28.446  3701  3748 I jxcore-log: 
,07-28 12:07:28.446  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:07:28.446  3701  3748 I jxcore-log: 
07-28 12:07:28.447  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-28 12:07:28.447  3701  3748 I jxcore-log: 
,07-28 12:07:28.448  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:07:28.448  3701  3748 I jxcore-log: 
,07-28 12:07:28.448  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.448  3701  3748 I jxcore-log: 
07-28 12:07:28.449  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.449  3701  3748 I jxcore-log: 
,07-28 12:07:28.449  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.449  3701  3748 I jxcore-log: 
,07-28 12:07:28.450  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.450  3701  3748 I jxcore-log: 
07-28 12:07:28.451  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.451  3701  3748 I jxcore-log: 
,07-28 12:07:28.452  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.452  3701  3748 I jxcore-log: 
,07-28 12:07:28.453  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.453  3701  3748 I jxcore-log: 
,07-28 12:07:28.453  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.453  3701  3748 I jxcore-log: 
,07-28 12:07:28.454  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.454  3701  3748 I jxcore-log: 
07-28 12:07:28.454  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.454  3701  3748 I jxcore-log: 
,07-28 12:07:28.455  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.455  3701  3748 I jxcore-log: 
,07-28 12:07:28.456  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.456  3701  3748 I jxcore-log: 
,07-28 12:07:28.456   872  1997 D DhcpClient: Broadcasting DHCPDISCOVER
07-28 12:07:28.456  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.456  3701  3748 I jxcore-log: 
,07-28 12:07:28.457  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.457  3701  3748 I jxcore-log: 
07-28 12:07:28.458  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.458  3701  3748 I jxcore-log: 
,07-28 12:07:28.458  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.458  3701  3748 I jxcore-log: 
,07-28 12:07:28.459  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.459  3701  3748 I jxcore-log: 
,07-28 12:07:28.459  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.459  3701  3748 I jxcore-log: 
07-28 12:07:28.460  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.460  3701  3748 I jxcore-log: 
,07-28 12:07:28.460  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:07:28.460  3701  3748 I jxcore-log: 
,07-28 12:07:28.461  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.461  3701  3748 I jxcore-log: 
,07-28 12:07:28.462  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.462  3701  3748 I jxcore-log: 
,07-28 12:07:28.462  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.462  3701  3748 I jxcore-log: 
07-28 12:07:28.463  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.463  3701  3748 I jxcore-log: 
07-28 12:07:28.463  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 12:07:28.463  3701  3748 I jxcore-log: 
,07-28 12:07:28.464  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:07:28.464  3701  3748 I jxcore-log: 
,07-28 12:07:28.464  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.464  3701  3748 I jxcore-log: 
,07-28 12:07:28.465  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 12:07:28.465  3701  3748 I jxcore-log: 
07-28 12:07:28.466  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
,07-28 12:07:28.466  3701  3748 I jxcore-log: 
07-28 12:07:28.466  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.466  3701  3748 I jxcore-log: 
,07-28 12:07:28.467  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-28 12:07:28.467  3701  3748 I jxcore-log: 
07-28 12:07:28.467  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:07:28.467  3701  3748 I jxcore-log: 
,07-28 12:07:28.467  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:07:28.467  3701  3748 I jxcore-log: 
,07-28 12:07:28.498   872  4095 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
07-28 12:07:28.498   872  1997 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds
,07-28 12:07:28.501   872  1997 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-28 12:07:28.513   872  4095 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-28 12:07:28.514   872  1997 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-28 12:07:28.519   372   870 D CommandListener: Setting iface cfg
,07-28 12:07:28.530   872  1997 D DhcpClient: Scheduling renewal in 86399s
07-28 12:07:28.530   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-28 12:07:28.531   872  1315 E native  : do suspend true
,07-28 12:07:28.545   872  1315 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-28 12:07:28.547   872  1315 D WifiConfigStore: No blacklist allowed without epno enabled
,07-28 12:07:28.548   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-28 12:07:28.549   872  1317 D ConnectivityService: Adding iface wlan0 to network 102,
,07-28 12:07:28.557   872  1315 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:07:28.600   872  1317 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-28 12:07:28.600   872  1317 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,07-28 12:07:28.603   872  1317 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,07-28 12:07:28.606   872  1317 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,07-28 12:07:28.611   872  1317 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-28 12:07:28.629   872  1317 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-28 12:07:28.643   872  1317 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-28 12:07:28.643   872  1317 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,07-28 12:07:28.643   872  1317 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-28 12:07:28.643   872  1315 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-28 12:07:28.643   872  1317 D ConnectivityService:    accepting network in place of null
07-28 12:07:28.644   872  1315 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-28 12:07:28.644   872  1317 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-28 12:07:28.649   872  4094 D NetlinkSocketObserver: NeighborEvent{elapsedMs=305383, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-28 12:07:28.662   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:28.686   372   870 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-28 12:07:28.689   872  1317 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-28 12:07:28.689   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:07:28.693   872  1317 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,07-28 12:07:28.697   872   889 D Tethering: MasterInitialState.processMessage what=3
,07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:07:28.706  3701  3701 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:07:28.709  3701  3701 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:07:28.711  3701  3748 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:07:28.711  3701  3748 I jxcore-log: 
,07-28 12:07:28.712  1810  1810 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-28 12:07:28.714   872  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.78,2a00:1450:4001:80b::200e
07-28 12:07:28.715  1949  1949 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-28 12:07:28.721  1949  1949 D SystemUpdateService: onCreate
,07-28 12:07:28.724  1949  1949 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-28 12:07:28.744  1949  1949 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-28 12:07:28.746  1949  2347 I iu.UploadsManager: num queued entries: 0
,07-28 12:07:28.753  1949  1949 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-28 12:07:28.754  1949  1949 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-28 12:07:28.756  3813  3813 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:07:28.761  1949  4110 I MDM     : [220] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
07-28 12:07:28.761  1949  4110 W BaseAppContext: Using Auth Proxy for data requests.
,07-28 12:07:28.762  3813  3813 D SprintDMHelper: simOperator: 
07-28 12:07:28.762  3813  3813 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-28 12:07:28.767  1949  4110 V GoogleAuthProtoRequest: [220] a.<init>: mAccountName set to: thalitester@gmail.com
,07-28 12:07:28.773  1949  4108 I SystemUpdateService: active receiver: enabled
,07-28 12:07:28.774  1949  2347 I iu.UploadsManager: num updated entries: 0
,07-28 12:07:28.777   872  4093 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:07:28 GMT], X-Android-Received-Millis=[1469700448777], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1469700448753]}
,07-28 12:07:28.779   872  1317 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-28 12:07:28.780   872  1317 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,07-28 12:07:28.780   872  1317 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
07-28 12:07:28.781   872  1317 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 12:07:28.789  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:07:28.795  1527  1527 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-28 12:07:28.810  1949  4108 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-28 12:07:28.816  1949  2347 I iu.SyncManager: NEXT; no task
,07-28 12:07:28.824  1949  4108 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-28 12:07:28.824  1949  4108 I SystemUpdateService: now status is 0 (complete)
07-28 12:07:28.824  1949  4108 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-28 12:07:28.824  1949  4108 I SystemUpdateService: file has been verified
07-28 12:07:28.824  1949  4108 I SystemUpdateService: OTA package size = 12249756
,07-28 12:07:28.836  1949  4108 I SystemUpdateService: showing system update notification
,07-28 12:07:28.849  1527  1994 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-28 12:07:28.849  1527  1994 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-28 12:07:28.849  1527  1994 I GLSUser : [GLSUser] Extracting token using key: Auth
07-28 12:07:28.849  1527  1994 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-28 12:07:28.866  1949  1949 D SystemUpdateService: onDestroy
,07-28 12:07:28.887  1949  4110 E MDM     : [220] SitrepService.a: Error sending sitrep.
,07-28 12:07:28.898  3362  4113 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,07-28 12:07:29.129  4098  4098 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-28 12:07:29.134  4098  4098 D AndroidRuntime: CheckJNI is OFF
,07-28 12:07:29.176  4098  4098 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-28 12:07:29.224  4098  4098 I Radio-JNI: register_android_hardware_Radio DONE
,07-28 12:07:29.249  4098  4098 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:07:29.258   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg,
07-28 12:07:29.259   872   885 I ActivityManager: Killing 3701:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,07-28 12:07:29.344   872   882 D GraphicsStats: Buffer count: 2
,07-28 12:07:29.344   872  1735 I WindowState: WIN DEATH: Window{934f939 u0 com.test.thalitest/com.test.thalitest.MainActivity}
07-28 12:07:29.344   872  1316 D WifiService: Client connection lost with reason: 4
,07-28 12:07:29.401   872   895 W PackageSettings: Skipping PackageSetting{6bb3572 com.example.hello/10273} due to missing metadata
,07-28 12:07:29.426   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
07-28 12:07:29.426   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,07-28 12:07:29.427   872   885 E ActivityManager: Failure starting process com.test.thalitest
07-28 12:07:29.427   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
07-28 12:07:29.427   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.427   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.427   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:07:29.427   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-28 12:07:29.428   872   895 I art     : Starting a blocking GC Explicit
07-28 12:07:29.428   872   885 I ActivityManager:   Force finishing activity ActivityRecord{5f5262a u0 com.test.thalitest/.MainActivity t2}
,07-28 12:07:29.440   872   882 W ActivityManager: Spurious death for ProcessRecord{ad18a4d 0:com.test.thalitest/u0a0}, curProc for 3701: null
,07-28 12:07:29.473   872   895 I art     : Explicit concurrent mark sweep GC freed 53944(3MB) AllocSpace objects, 9(220KB) LOS objects, 33% free, 29MB/43MB, paused 737us total 44.127ms
,07-28 12:07:29.501   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-28 12:07:29.506  4098  4098 I art     : System.exit called, status: 0
,07-28 12:07:29.506  4098  4098 I AndroidRuntime: VM exiting with result code 0.
,07-28 12:07:29.513   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-28 12:07:29.527   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,07-28 12:07:29.532  4039  4039 D BluetoothMapAppObserver: onReceive
,07-28 12:07:29.532  4039  4039 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-28 12:07:29.534   872  1307 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-28 12:07:29.535  1974  2060 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-28 12:07:29.539  3529  3529 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,07-28 12:07:29.562  1666  1666 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-28 12:07:29.569  1745  1745 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-28 12:07:29.593   872  1397 I ActivityManager: Start proc 4132:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-28 12:07:29.595  1666  4137 I Keyboard.Facilitator.DecoderInitializer: run()
,07-28 12:07:29.610  1666  4137 I Decoder : createOrResetDecoder
,07-28 12:07:29.627   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-28 12:07:29.632  1527  1527 I ConfigService: onCreate
,07-28 12:07:29.637  4132  4132 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-28 12:07:29.646  1527  4145 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-28 12:07:29.646  1527  4145 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-28 12:07:29.646  1527  4145 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
07-28 12:07:29.648  1527  4145 W SQLiteOpenHelper: Opened config.db in read-only mode
,07-28 12:07:29.656   872  1735 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3701 uid 10000
,07-28 12:07:29.657  1666  1666 I Keyboard.Facilitator: onFinishInput()
,07-28 12:07:29.662  1666  4137 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-28 12:07:29.666  1758  1835 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,07-28 12:07:29.667   872   884 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
07-28 12:07:29.668   872   884 E PackageManager: Failed to write settings, restoring backup
07-28 12:07:29.668   872   884 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-28 12:07:29.668   872   884 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-28 12:07:29.668   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-28 12:07:29.668   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-28 12:07:29.668   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-28 12:07:29.668   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.668   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.668   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-28 12:07:29.673   872   885 E DropBoxManagerService: Can't write: system_server_wtf
07-28 12:07:29.673   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-28 12:07:29.673   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:07:29.673   872   885 E DropBoxManagerService: 	... 13 more
,07-28 12:07:29.678   872  1397 I ActivityManager: Start proc 4146:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
07-28 12:07:29.679  1758  1835 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-28 12:07:29.679  1758  1835 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1758
07-28 12:07:29.679  1758  1835 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.679  1758  1835 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:07:29.681   872  1735 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-28 12:07:29.682   872  4151 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:07:29.682   872  4151 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:07:29.682   872  4151 E DropBoxManagerService: 	... 5 more
,07-28 12:07:29.688  1758  1835 I Process : Sending signal. PID: 1758 SIG: 9
,07-28 12:07:29.714  1666  4137 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-28 12:07:29.716  1666  4137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-28 12:07:29.716  1666  4137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
07-28 12:07:29.717  1666  4137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-28 12:07:29.717  1666  4137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
07-28 12:07:29.718  1666  4137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
07-28 12:07:29.718  1666  4137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-28 12:07:29.719  1666  4137 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-28 12:07:29.719  1666  4137 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
,07-28 12:07:29.719  1666  4137 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-28 12:07:29.719  1666  4137 I Keyboard.Facilitator.RecurringTaskScheduler: run()
07-28 12:07:29.719  1666  4137 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-28 12:07:29.719  1666  4137 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-28 12:07:29.726   872  1724 D GraphicsStats: Buffer count: 1
,07-28 12:07:29.726   872   883 I WindowState: WIN DEATH: Window{c02cc4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,07-28 12:07:29.739   872  1764 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1758) has died
07-28 12:07:29.740   872  1764 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
07-28 12:07:29.741   872  1764 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,07-28 12:07:29.762   872   885 I ActivityManager: Start proc 4163:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-28 12:07:29.775  4132  4132 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-28 12:07:29.808  4163  4163 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:29.808  4163  4163 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:07:29.808  4163  4163 D AndroidRuntime: Shutting down VM
,07-28 12:07:29.817  4163  4163 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:07:29.817  4163  4163 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4163
07-28 12:07:29.817  4163  4163 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 12:07:29.817  4163  4163 E AndroidRuntime: 	... 10 more
07-28 12:07:29.819   872  2988 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-28 12:07:29.820   872  4178 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:07:29.820   872  4178 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop126.tmp: open failed: EROFS (Read-only file system)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:07:29.820   872  4178 E DropBoxManagerService: 	... 5 more
07-28 12:07:29.820  4163  4163 I Process : Sending signal. PID: 4163 SIG: 9
07-28 12:07:29.828   872  1739 I ActivityManager: Start proc 4180:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
07-28 12:07:29.845   872  3091 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 4163) has died
07-28 12:07:29.847   872  3091 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,07-28 12:07:29.851  4132  4179 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.853  4132  4161 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: Couldn't open contacts2.db for writing (will try read-only):
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPoo,l.java:177)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at com.android.providers.contacts.LegacyApiSupport.<init>(LegacyApiSupport.java:530)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.initForDefaultLocale(ContactsProvider2.java:1596)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1687)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.853  4132  4161 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:07:29.861   872  1735 I ActivityManager: Start proc 4192:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-28 12:07:29.871  1949  4177 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-28 12:07:29.875  1949  4177 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-28 12:07:29.886  1949  4177 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
07-28 12:07:29.886  1949  4177 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
07-28 12:07:29.885  4180  4180 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,07-28 12:07:29.904  4192  4192 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:29.904  4192  4192 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-28 12:07:29.905  4192  4192 D AndroidRuntime: Shutting down VM
,07-28 12:07:29.907  1527  1527 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,07-28 12:07:29.908  1527  1527 D AndroidRuntime: Shutting down VM
,07-28 12:07:29.909  1527  1527 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:07:29.909  1527  1527 E AndroidRuntime: Process: com.google.process.gapps, PID: 1527
07-28 12:07:29.909  1527  1527 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
07-28 12:07:29.909  1527  1527 E AndroidRuntime: 	... 8 more
07-28 12:07:29.913  4192  4192 E AndroidRuntime: FATAL EXCEPTION: main
07-28 12:07:29.913  4192  4192 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4192
07-28 12:07:29.913  4192  4192 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.913  4192  4,192 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-28 12:07:29.913  4192  4192 E AndroidRuntime: 	... 10 more
07-28 12:07:29.915   872  4207 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:07:29.915   872  4207 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:07:29.915   872  4207 E DropBoxManagerService: 	... 5 more
07-28 12:07:29.921   872  4208 E DropBoxManagerService: Can't write: system_app_crash
07-28 12:07:29.921   872  4208 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-28 12:07:29.921   872  4208 E DropBoxManagerService: 	... 5 more
07-28 12:07:29.921   872  1724 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-28 12:07:29.922  4192  4192 I Process : Sending signal. PID: 4192 SIG: 9
07-28 12:07:29.922  1527  1527 I Process : Sending signal. PID: 1527 SIG: 9
07-28 12:07:29.932   872  2988 I ActivityManager: Killing 3581:com.google.android.apps.docs/u0a46 (adj 15): empty #17
,07-28 12:07:29.967   872  1316 D WifiService: Client connection lost with reason: 4
07-28 12:07:29.971  4132  4161 E SQLiteLog: (8) statement aborts at 43: [CREATE TABLE IF NOT EXISTS presence_db.presence (presence_data_id INTEGER PRIMARY KEY REFERENCES data(_id),protocol INTEGER NOT NULL,custom_protocol TEXT,im_handle TEXT,im_account TEXT
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.976  4132  4179 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-28 12:07:29.976  4132  4179 E AndroidRuntime: Process: android.process.acore, PID: 4132
07-28 12:07:29.976  4132  4179 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-28 12:07:29.976  4132  4179 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-28 12:07:29.977  4132  4161 I Process : Sending signal. PID: 4132 SIG: 9
,07-28 12:07:29.996   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
