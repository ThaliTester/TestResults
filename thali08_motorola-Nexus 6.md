#### Test 757892686f45c73_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-26 15:23:31.957   871  1948 D NetlinkSocketObserver: NeighborEvent{elapsedMs=308850, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-26 15:23:32.673  3752  3752 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-26 15:23:32.678  3752  3752 D AndroidRuntime: CheckJNI is OFF
07-26 15:23:32.713  3752  3752 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-26 15:23:32.755  3752  3752 I Radio-JNI: register_android_hardware_Radio DONE
07-26 15:23:32.775  3752  3752 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-26 15:23:32.781   871  2843 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-26 15:23:32.845   871  2843 I ActivityManager: Start proc 3761:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-26 15:23:32.850  3752  3752 D AndroidRuntime: Shutting down VM
07-26 15:23:32.934  3761  3761 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-26 15:23:32.963  3761  3761 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-26 15:23:32.983  3761  3761 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 9869-9877)
07-26 15:23:32.983  3761  3761 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:23:33.000  3761  3761 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2953b1a}
07-26 15:23:33.000  3761  3761 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:23:33.000  3761  3761 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-26 15:23:33.008  3761  3761 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-26 15:23:33.010  3761  3761 E SysUtils: ApplicationContext is null in ApplicationStatus
07-26 15:23:33.027  3761  3761 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-26 15:23:33.041  3761  3761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:23:33.041  3761  3761 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:23:33.042  3761  3761 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-26 15:23:33.042  3761  3761 I Adreno  : Build Date                       : 10/20/15
07-26 15:23:33.042  3761  3761 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-26 15:23:33.042  3761  3761 I Adreno  : Local Branch                     : M14
07-26 15:23:33.042  3761  3761 I Adreno  : Remote Branch                    : 
07-26 15:23:33.042  3761  3761 I Adreno  : Remote Branch                    : 
07-26 15:23:33.042  3761  3761 I Adreno  : Reconstruct Branch               : 
,07-26 15:23:33.126   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b8044e5:true
,07-26 15:23:33.176  3761  3761 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-26 15:23:33.192  3761  3761 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-26 15:23:33.293  3761  3798 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-26 15:23:33.316  3761  3785 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-26 15:23:33.374  3761  3798 I OpenGLRenderer: Initialized EGL, version 1.4
,07-26 15:23:33.443   871   889 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +550ms (total +639ms)
,07-26 15:23:33.447  1645  1645 I Keyboard.Facilitator: onFinishInput()
,07-26 15:23:33.556  3761  3761 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3761
,07-26 15:23:33.801  3761  3761 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-26 15:23:33.887  3761  3801 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1680148176
,07-26 15:23:33.895  3761  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-26 15:23:33.895  3761  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-26 15:23:33.895  3761  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-26 15:23:33.895  3761  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-26 15:23:33.895  3761  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-26 15:23:33.896  3761  3801 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@689ed39 added. We now have 1 listener(s)
,07-26 15:23:33.900  3761  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-26 15:23:33.900  3761  3801 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-26 15:23:33.901  3761  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:23:33.901  3761  3801 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-26 15:23:33.905  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-26 15:23:33.906  3761  3801 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@593bd2c added. We now have 1 listener(s)
07-26 15:23:33.906  3761  3801 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:23:33.913   871  1308 D WifiService: New client listening to asynchronous messages
,07-26 15:23:33.916  3761  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:23:33.916  3761  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-26 15:23:33.917  3761  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-26 15:23:33.917  3761  3801 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-26 15:23:33.920  3761  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:23:33.920  3761  3801 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-26 15:23:33.933  3761  3801 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:33.933  3761  3801 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:33.933  3761  3801 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-26 15:23:33.933  3761  3801 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:23:33.937  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:33.941  3761  3801 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-26 15:23:33.942  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:33.972  3761  3761 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-26 15:23:34.917  3761  3809 W jxcore-log: Initializing JXcore engine
,07-26 15:23:34.917  3761  3809 W jxcore-log: JXcore engine is ready
,07-26 15:23:34.954  3809  3809 W Thread-342: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-26 15:23:34.954  3809  3809 W Thread-342: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[13154]" dev="sockfs" ino=13154 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-26 15:23:34.954  3809  3809 W Thread-342: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-26 15:23:34.954  3809  3809 W Thread-342: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[26872]" dev="sockfs" ino=26872 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-26 15:23:34.967  3761  3809 W jxcore-log: Starting JXcore engine
,07-26 15:23:35.048  3761  3809 W jxcore-log: Platform android
07-26 15:23:35.048  3761  3809 W jxcore-log: 
,07-26 15:23:35.048  3761  3809 W jxcore-log: Process ARCH arm
07-26 15:23:35.048  3761  3809 W jxcore-log: 
,07-26 15:23:35.212  3761  3809 I jxcore-log: JXcore Cordova bridge is ready!
07-26 15:23:35.212  3761  3809 I jxcore-log: 
,07-26 15:23:35.212  3761  3809 W jxcore-log: JXcore engine is started
,07-26 15:23:35.225  3761  3801 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-26 15:23:35.231  3761  3761 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-26 15:23:35.703  1537  1537 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-26 15:23:35.704  1537  1537 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:23:35.730  1537  2204 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-26 15:23:35.730  1537  2204 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-26 15:23:35.731  1537  2204 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:23:35.731  1537  2204 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-26 15:23:35.744  3415  3813 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-26 15:23:35.744  3415  3813 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jdm.a(PG:82)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jcs.o(PG:406)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jcn.a(PG:1379)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jcs.i(PG:143)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at blb.a(PG:3937)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at czp.a(PG:18188)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at czp.a(PG:9081)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at czq.run(PG:1686)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-26 15:23:35.744  3415  3813 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jdj.a(PG:4091)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jdj.a(PG:1125)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jdm.a(PG:77)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	... 12 more
07-26 15:23:35.744  3415  3813 E HttpOperation: Caused by: faj: BadAuthentication
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at fal.a(PG:38)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	at jdj.a(PG:4089)
07-26 15:23:35.744  3415  3813 E HttpOperation: 	... 14 more
,07-26 15:23:35.786  1537  1945 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-26 15:23:35.786  1537  1945 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-26 15:23:35.787  1537  1945 I GLSUser : [GLSUser] Extracting token using key: Auth
07-26 15:23:35.787  1537  1945 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-26 15:23:35.799  3415  3813 E HttpOperation: [getmobileexperiments] Unexpected exception
07-26 15:23:35.799  3415  3813 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jdm.a(PG:82)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jcs.o(PG:406)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jcn.a(PG:1379)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jcs.i(PG:143)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at hec.a(PG:42)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at hee.a(PG:102)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at czr.a(PG:65)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at kka.a(PG:108)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at czp.a(PG:19176)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at czp.a(PG:9081)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at czq.run(PG:1686)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-26 15:23:35.799  3415  3813 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jdj.a(PG:4091)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jdj.a(PG:1125)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jdm.a(PG:77)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	... 15 more
07-26 15:23:35.799  3415  3813 E HttpOperation: Caused by: faj: BadAuthentication
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at fal.a(PG:38)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	at jdj.a(PG:4089)
07-26 15:23:35.799  3415  3813 E HttpOperation: 	... 17 more
,07-26 15:23:35.800  3415  3813 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-26 15:23:35.800  3415  3813 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jdm.a(PG:82)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jcs.o(PG:406)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jcn.a(PG:1379)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jcs.i(PG:143)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at hec.a(PG:42)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at hee.a(PG:102)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at czr.a(PG:65)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at kka.a(PG:108)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at czp.a(PG:19176)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at czp.a(PG:9081)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at czq.run(PG:1686)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jdj.a(PG:4091)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jdj.a(PG:1125)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jdm.a(PG:77)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	... 15 more
07-26 15:23:35.800  3415  3813 E ExperimentLoader: Caused by: faj: BadAuthentication
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at fal.a(PG:38)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	at jdj.a(PG:4089)
07-26 15:23:35.800  3415  3813 E ExperimentLoader: 	... 17 more
,07-26 15:23:35.909   871   883 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 283643, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-26 15:23:45.387  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-26 15:23:45.387  3761  3809 I jxcore-log: 
,07-26 15:23:45.390  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-26 15:23:45.390  3761  3809 I jxcore-log: 
,07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:45.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:23:45.411  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:23:45.413  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-26 15:23:45.413  3761  3809 I jxcore-log: 
,07-26 15:23:45.415  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-26 15:23:45.415  3761  3809 I jxcore-log: 
,07-26 15:23:45.750  3761  3809 D ExecuteNativeTests: Running unit tests
,07-26 15:23:45.811  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:23:45.811  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea added. We now have 2 listener(s)
07-26 15:23:45.812  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-26 15:23:45.812  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:23:45.812  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:23:45.813  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:23:45.813  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db added. We now have 2 listener(s)
07-26 15:23:45.813  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:23:45.813  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:23:45.820  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:45.828  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-26 15:23:45.832  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:23:45.832  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:23:45.835  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-26 15:23:45.837  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:23:45.837  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:23:45.838  3761  3809 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-26 15:23:45.838  3761  3809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:23:45.838  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:23:45.839  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-26 15:23:45.839  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:23:45.839  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:45.840  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:45.840  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:45.840  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:45.840  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:45.840  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.841  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:23:45.841  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:23:45.841  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea removed from the list
07-26 15:23:45.841  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:45.841  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db removed from the list
,07-26 15:23:45.852  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:45.853  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:45.853  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:45.854  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:45.854  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:45.855  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:23:45.855  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:23:45.855  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:23:45.855  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
,07-26 15:23:45.857  3761  3809 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-26 15:23:45.857  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:23:45.857  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:23:45.857  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:45.857  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:45.857  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.857  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:45.858  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:45.858  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:45.858  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:45.858  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:23:45.858  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.858  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:45.858  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.858  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:45.860  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:45.860  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:45.860  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:45.860  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list,
07-26 15:23:45.865  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:23:45.865  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:23:45.865  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-26 15:23:45.865  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-26 15:23:45.865  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:23:45.865  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
,07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:23:45.866  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,07-26 15:23:45.867  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-26 15:23:45.867  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:23:45.867  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:23:45.867  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:23:45.867  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-26 15:23:45.867  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:45.867  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:45.867  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:45.867  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:45.867  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.867  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:45.867  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:45.867  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:45.867  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:45.867  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:45.867  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.867  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:45.867  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.867  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:45.869  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:45.869  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:45.869  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:45.869  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:45.869  3761  3809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:23:45.871  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:23:45.874  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:23:45.874  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:45.874  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:45.874  3761  380,9 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:45.874  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:45.874  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:45.874  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:45.874  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:45.876  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:45.876  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:23:45.876  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:23:45.876  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:23:45.876  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:23:45.876  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:23:45.878  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:45.879  3761  3809 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:23:45.879  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:23:45.880  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:45.890  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:23:45.892  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:23:45.892  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:23:45.894  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-26 15:23:45.898  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
07-26 15:23:45.899  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-26 15:23:45.899  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 15:23:45.900  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-26 15:23:45.901  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:23:45.905  2540  2720 D BtGatt.GattService: registerClient() - UUID=872609b6-4bd4-4c6d-b5a8-e70190ae3248
07-26 15:23:45.907  2540  2560 D BtGatt.GattService: onClientRegistered() - UUID=872609b6-4bd4-4c6d-b5a8-e70190ae3248, clientIf=5
07-26 15:23:45.908  3761  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-26 15:23:45.909  2540  2551 D BtGatt.GattService: start scan with filters
07-26 15:23:45.911  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-26 15:23:45.911  2540  2565 D BtGatt.ScanManager: handling starting scan
07-26 15:23:45.912  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-26 15:23:45.912  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-26 15:23:45.912  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-26 15:23:45.913  2540  2565 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
07-26 15:23:45.915  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-26 15:23:45.915  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-26 15:23:45.916  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-26 15:23:45.920  2540  2560 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-26 15:23:45.920  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.921  2540  2565 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-26 15:23:45.923  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-26 15:23:45.931  2540  2560 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-26 15:23:45.931  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.932  2540  2565 D BtGatt.ScanManager: Starting BLE batch scan
07-26 15:23:45.932  2540  2565 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-26 15:23:45.938  3761  3809 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:23:45.938  3761  3761 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:23:45.938  3761  3761 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-26 15:23:45.942  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:45.942  2540  2560 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-26 15:23:45.942  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.942  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:45.943  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.943  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 15:23:45.943  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:23:45.943  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:23:45.943  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:23:45.943  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:23:45.944  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:23:45.944  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-26 15:23:45.945  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:23:45.945  2540  2720 D BtGatt.GattService: stopScan() - queue size =1
07-26 15:23:45.946  2540  2551 D BtGatt.GattService: unregisterClient() - clientIf=5
07-26 15:23:45.946  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:23:45.946  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-26 15:23:45.946  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-26 15:23:45.946  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-26 15:23:45.947  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-26 15:23:45.947  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:45.948  2540  2560 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-26 15:23:45.948  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.948  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-26 15:23:45.948  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:23:45.948  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:23:45.949  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:23:45.950  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:23:45.950  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:45.950  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.950  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:23:45.950  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:23:45.950  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:45.950  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:45.950  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:45.950  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:45.950  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:45.950  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:45.951  3761  3809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:23:45.953  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:23:45.955  2540  2560 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-26 15:23:45.955  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.955  2540  2565 D BtGatt.ScanManager: stopping BLe Batch
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:45.960  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:45.961  2540  2560 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-26 15:23:45.961  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.962  2540  2565 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 15:23:45.963  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:45.963  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:23:45.963  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:23:45.963  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:23:45.963  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:23:45.963  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:23:45.965  3761  3809 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:23:45.965  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:23:45.966  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:45.967  2540  2560 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-26 15:23:45.967  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.968  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:45.968  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:23:45.968  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:23:45.969  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:23:45.974  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-26 15:23:45.974  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 15:23:45.974  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-26 15:23:45.974  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:23:45.976  2540  2720 D BtGatt.GattService: registerClient() - UUID=757d6018-aca6-4331-8fd5-650a463bda53
07-26 15:23:45.977  2540  2560 D BtGatt.GattService: onClientRegistered() - UUID=757d6018-aca6-4331-8fd5-650a463bda53, clientIf=5
07-26 15:23:45.977  3761  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-26 15:23:45.978  2540  2551 D BtGatt.GattService: start scan with filters
07-26 15:23:45.982  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-26 15:23:45.982  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-26 15:23:45.982  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-26 15:23:45.982  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-26 15:23:45.982  2540  2565 D BtGatt.ScanManager: handling starting scan
07-26 15:23:45.986  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-26 15:23:45.986  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-26 15:23:45.986  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
07-26 15:23:45.989  2540  2560 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-26 15:23:45.989  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.989  2540  2565 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-26 15:23:45.990  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-26 15:23:45.994  2540  2560 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-26 15:23:45.994  3761  3761 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:23:45.994  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:45.995  3761  3761 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-26 15:23:45.995  2540  2565 D BtGatt.ScanManager: Starting BLE batch scan
07-26 15:23:45.995  2540  2565 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-26 15:23:45.995  3761  3809 I io.jxcore.node.ConnectionHelper: start: OK
07-26 15:23:45.998  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:45.998  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:45.998  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:45.998  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 15:23:45.998  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:23:45.998  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:23:45.999  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:23:45.999  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:23:46.000  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:23:46.000  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-26 15:23:46.001  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:23:46.002  2540  2552 D BtGatt.GattService: stopScan() - queue size =1
07-26 15:23:46.002  2540  2720 D BtGatt.GattService: unregisterClient() - clientIf=5
07-26 15:23:46.003  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:23:46.003  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-26 15:23:46.003  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-26 15:23:46.003  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-26 15:23:46.004  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-26 15:23:46.005  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:46.005  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-26 15:23:46.005  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:23:46.006  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:23:46.006  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:23:46.010  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:23:46.009  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.010  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:23:46.010  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.010  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:46.010  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:23:46.010  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.010  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.011  2540  2560 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-26 15:23:46.011  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.011  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.011  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.011  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.013  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.014  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.017  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.017  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.017  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.017  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.019  3761  3809 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-26 15:23:46.020  2540  2560 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-26 15:23:46.020  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.024  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:23:46.030  2540  2560 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-26 15:23:46.030  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.030  2540  2565 D BtGatt.ScanManager: stopping BLe Batch
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:46.036  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:46.040  2540  2560 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-26 15:23:46.041  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.041  2540  2565 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-26 15:23:46.041  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:46.042  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:23:46.043  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:23:46.043  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:23:46.043  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:23:46.043  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:23:46.051  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:46.052  2540  2560 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-26 15:23:46.053  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:23:46.054  3761  3809 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,07-26 15:23:46.055  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-26 15:23:46.057  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:46.062  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-26 15:23:46.063  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-26 15:23:46.063  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-26 15:23:46.071  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-26 15:23:46.071  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 15:23:46.071  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-26 15:23:46.073  3761  3809 D BluetoothAdapter: STATE_ON
,07-26 15:23:46.078  2540  2720 D BtGatt.GattService: registerClient() - UUID=da0c0dd8-813f-434e-86c5-56e12b262d14
,07-26 15:23:46.080  2540  2560 D BtGatt.GattService: onClientRegistered() - UUID=da0c0dd8-813f-434e-86c5-56e12b262d14, clientIf=5
,07-26 15:23:46.081  3761  3772 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-26 15:23:46.083  2540  2552 D BtGatt.GattService: start scan with filters
,07-26 15:23:46.091  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-26 15:23:46.091  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-26 15:23:46.091  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-26 15:23:46.091  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
07-26 15:23:46.091  2540  2565 D BtGatt.ScanManager: handling starting scan
,07-26 15:23:46.098  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-26 15:23:46.098  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK,
,07-26 15:23:46.098  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-26 15:23:46.102  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-26 15:23:46.108  3761  3809 I io.jxcore.node.ConnectionHelper: start: OK
,07-26 15:23:46.108  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.108  3761  3761 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:23:46.109  3761  3761 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-26 15:23:46.109  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.109  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.109  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 15:23:46.109  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,07-26 15:23:46.110  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:23:46.110  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:23:46.110  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:23:46.110  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-26 15:23:46.110  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-26 15:23:46.111  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:23:46.112  2540  2560 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-26 15:23:46.112  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.113  2540  2565 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
07-26 15:23:46.112  2540  2720 D BtGatt.GattService: stopScan() - queue size =1
07-26 15:23:46.114  2540  2552 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 15:23:46.115  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,07-26 15:23:46.115  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-26 15:23:46.115  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-26 15:23:46.115  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-26 15:23:46.115  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-26 15:23:46.117  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:46.117  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-26 15:23:46.117  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:23:46.118  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:23:46.119  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:23:46.123  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-26 15:23:46.123  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:23:46.123  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:46.123  3761  3761 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.123  3761  3761 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-26 15:23:46.124  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:23:46.124  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:23:46.124  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:23:46.124  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.125  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.126  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:23:46.127  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.127  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.127  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
,07-26 15:23:46.127  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.128  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.129  2540  2560 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-26 15:23:46.129  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.129  2540  2565 D BtGatt.ScanManager: Starting BLE batch scan
07-26 15:23:46.130  2540  2565 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,07-26 15:23:46.128  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.130  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.131  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:23:46.131  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.131  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.131  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
,07-26 15:23:46.132  3761  3809 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-26 15:23:46.133  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.133  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.133  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:23:46.133  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.133  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.134  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.134  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.134  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:23:46.134  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.134  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.134  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.134  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.134  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.134  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.136  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:23:46.136  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.136  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.137  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.138  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:23:46.138  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.138  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:23:46.138  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.139  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.139  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.139  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.139  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.139  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:23:46.139  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.139  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.139  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.139  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.139  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.139  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.141  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:23:46.141  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.141  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.141  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.142  3761  3809 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,07-26 15:23:46.142  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.142  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:23:46.143  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:23:46.143  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.143  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.143  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.144  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.144  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:23:46.144  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.144  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:23:46.144  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.144  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.145  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.145  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.146  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:23:46.146  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:23:46.147  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.147  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
,07-26 15:23:46.147  3761  3809 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-26 15:23:46.148  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:23:46.148  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:23:46.148  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:23:46.148  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.148  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.148  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.148  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
,07-26 15:23:46.148  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.148  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.148  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:23:46.148  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
,07-26 15:23:46.148  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.149  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.149  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.150  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
07-26 15:23:46.150  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.150  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:23:46.150  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.151  2540  2560 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-26 15:23:46.151  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:23:46.151  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:23:46.153  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:23:46.153  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-26 15:23:46.153  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:23:46.154  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-26 15:23:46.154  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-26 15:23:46.154  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:23:46.154  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.154  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.155  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.155  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.155  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.155  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.155  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:23:46.155  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.155  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.155  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.156  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.156  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.156  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.158  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.159  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.159  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.159  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.160  3761  3809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:23:46.161  3761  3809 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-26 15:23:46.161  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-26 15:23:46.167  3761  3809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:23:46.167  3761  3809 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-26 15:23:46.167  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-26 15:23:46.167  2540  2560 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
07-26 15:23:46.168  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.168  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-26 15:23:46.169  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510],
07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,07-26 15:23:46.170  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,07-26 15:23:46.171  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-26 15:23:46.171  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-26 15:23:46.171  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-26 15:23:46.171  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-26 15:23:46.171  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,07-26 15:23:46.171  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-26 15:23:46.172  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-26 15:23:46.172  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-26 15:23:46.172  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-26 15:23:46.172  3761  3809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-26 15:23:46.172  3761  3809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:23:46.172  3761  3809 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-26 15:23:46.172  3761  3809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:23:46.172  3761  3809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-26 15:23:46.173  3761  3809 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-26 15:23:46.173  3761  3809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-26 15:23:46.173  3761  3809 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...,
07-26 15:23:46.173  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-26 15:23:46.176  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-26 15:23:46.176  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
,07-26 15:23:46.176  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-26 15:23:46.177  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-26 15:23:46.177  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-26 15:23:46.177  3761  3809 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-26 15:23:46.177  3761  3809 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,07-26 15:23:46.177  3761  3809 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-26 15:23:46.178  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.178  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.178  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.178  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.178  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-26 15:23:46.178  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.178  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-26 15:23:46.179  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.179  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.179  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
,07-26 15:23:46.179  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.179  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.179  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.180  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.180  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
07-26 15:23:46.180  3761  3818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 406
07-26 15:23:46.181  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.181  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:23:46.181  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.181  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.181  2540  2560 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-26 15:23:46.181  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.181  2540  2565 D BtGatt.ScanManager: stopping BLe Batch
07-26 15:23:46.182  3761  3809 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-26 15:23:46.182  3761  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 406),
07-26 15:23:46.182  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.182  3761  3817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 406)
07-26 15:23:46.182  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.182  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.182  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:23:46.182  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.182  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.183  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.183  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.183  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.183  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.183  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-26 15:23:46.183  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.183  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.183  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.184  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.184  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:23:46.184  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.184  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.185  3761  3809 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-26 15:23:46.185  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.185  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:23:46.185  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.185  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.186  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.186  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.186  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
,07-26 15:23:46.186  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.186  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.186  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.186  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.186  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.186  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.186  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.187  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:23:46.187  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.187  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.187  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.188  3761  3809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
,07-26 15:23:46.188  3761  3809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-26 15:23:46.188  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:23:46.188  3761  3809 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-26 15:23:46.188  3761  3809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,07-26 15:23:46.188  3761  3809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-26 15:23:46.189  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:23:46.189  3761  3809 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-26 15:23:46.189  3761  3809 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-26 15:23:46.189  3761  3809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
,07-26 15:23:46.189  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:23:46.189  3761  3809 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-26 15:23:46.190  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.190  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:23:46.190  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.190  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.190  2540  2560 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-26 15:23:46.190  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
07-26 15:23:46.190  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:23:46.190  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.190  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
,07-26 15:23:46.190  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.190  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.190  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.190  2540  2565 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-26 15:23:46.190  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.190  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.191  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.191  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.192  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:23:46.192  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.192  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.192  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.193  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.193  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.193  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.193  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.193  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.193  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.193  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:23:46.193  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.193  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.193  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:23:46.194  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.194  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.194  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.194  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.194  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.194  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:23:46.194  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.194  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.194  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.194  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.194  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.194  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.194  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.194  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.194  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.194  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.194  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.194  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.194  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.195  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.195  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery,
07-26 15:23:46.195  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.195  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.196  3761  3809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-26 15:23:46.197  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:23:46.198  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-26 15:23:46.198  3761  3809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-26 15:23:46.198  2540  2560 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
07-26 15:23:46.198  3761  3809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-26 15:23:46.198  2540  2560 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:23:46.198  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-26 15:23:46.198  3761  3761 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-26 15:23:46.198  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:23:46.199  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.199  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,07-26 15:23:46.199  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-26 15:23:46.199  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-26 15:23:46.199  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.199  3761  3809 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-26 15:23:46.199  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
,07-26 15:23:46.199  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.199  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:23:46.199  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:23:46.199  3761  3761 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-26 15:23:46.199  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode,
07-26 15:23:46.199  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.199  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.200  3761  3819 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-26 15:23:46.200  3761  3819 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,07-26 15:23:46.200  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:46.200  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.200  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:23:46.200  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.200  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:23:46.201  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.201  3761  3761 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-26 15:23:46.201  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:23:46.201  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:23:46.201  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.201  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.201  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.201  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.201  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.201  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.201  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:23:46.201  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.201  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.201  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.201  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.202  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.202  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.203  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.203  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.204  3761  3809 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,07-26 15:23:46.204  3761  3809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-26 15:23:46.205  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-26 15:23:46.205  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-26 15:23:46.205  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.205  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.205  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.205  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:23:46.206  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.206  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.206  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.206  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.206  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.206  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.206  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.206  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.207  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.207  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.208  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.208  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.208  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.208  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.213  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.213  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.213  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:23:46.213  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.213  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.213  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.214  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.214  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.214  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.214  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.214  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:23:46.214  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.214  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.214  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.216  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.216  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.216  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.216  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
,07-26 15:23:46.217  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:23:46.217  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:23:46.217  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:23:46.218  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:23:46.218  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.218  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:23:46.218  3761  3809 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@44cb8ea not in the list
07-26 15:23:46.218  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.218  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.218  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:23:46.218  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.219  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.219  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:23:46.219  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:23:46.220  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:23:46.220  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:23:46.220  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:23:46.220  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3fe37db not in the list
07-26 15:23:46.222  3761  3809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-26 15:23:46.222  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:23:46.222  3761  3809 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-26 15:23:46.222  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-26 15:23:46.222  3761  3809 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-26 15:23:46.223  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-26 15:23:46.225  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-26 15:23:46.225  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-26 15:23:46.226  3761  3809 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-26 15:23:46.227  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:23:46.227  3761  3809 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-26 15:23:46.227  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-26 15:23:46.227  3761  3809 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-26 15:23:46.227  3761  3809 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-26 15:23:46.228  3761  3809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-26 15:23:46.228  3761  3809 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-26 15:23:46.229  3761  3809 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-26 15:23:46.229  3761  3809 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-26 15:23:46.229  3761  3809 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-26 15:23:46.229  3761  3809 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-26 15:23:46.231  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:23:46.231  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ec33145 added. We now have 2 listener(s)
07-26 15:23:46.231  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:23:46.234  3761  3809 D BluetoothAdapter: enable(): BT is already enabled..!
07-26 15:23:46.234   871  1675 D WifiService: setWifiEnabled: true pid=3761, uid=10000
07-26 15:23:46.234   871  1675 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:23:46.235  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:23:46.236  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@27d309a added. We now have 3 listener(s)
07-26 15:23:46.236  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:23:46.241  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:23:46.242  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@538cdcb added. We now have 4 listener(s)
07-26 15:23:46.242  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:23:46.243  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:23:46.243  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@de5a9a8 added. We now have 5 listener(s)
07-26 15:23:46.243  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:23:46.245   871  2303 D WifiService: setWifiEnabled: false pid=3761, uid=10000
07-26 15:23:46.245   871  2303 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
07-26 15:23:46.249  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:23:46.249  2540  2556 D BluetoothAdapterState: Current state: ON, message: 23
07-26 15:23:46.249  2540  2556 D BluetoothAdapterProperties: Setting state to 13
07-26 15:23:46.250  2540  2556 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:23:46.250  2540  2556 D BluetoothAdapterProperties: onBluetoothDisable()
07-26 15:23:46.252  2540  2556 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:23:46.252  2540  2560 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:23:46.253  2540  2556 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-26 15:23:46.256  2540  2540 D HeadsetService: Received stop request...Stopping profile...
,07-26 15:23:46.258  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
07-26 15:23:46.259   871  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
07-26 15:23:46.259   871  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-26 15:23:46.259   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:23:46.259   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-26 15:23:46.260   871   871 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:46.261  1737  1869 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:46.261   871   871 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:46.261   871   871 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:46.261  1353  1821 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:46.263  1353  1353 D HeadsetProfile: Bluetooth service disconnected
07-26 15:23:46.267  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:46.267  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:46.268  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.268  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:46.268  2540  2540 D A2dpService: Received stop request...Stopping profile...
07-26 15:23:46.268  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
07-26 15:23:46.268  2540  2737 D A2dpStateMachine: Exit Disconnected: -1
07-26 15:23:46.271  1353  1353 D BluetoothA2dp: Proxy object disconnected
07-26 15:23:46.271   871   871 D BluetoothA2dp: Proxy object disconnected
07-26 15:23:46.271  2540  2540 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:46.271  2540  2540 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:46.271  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:46.271  2540  2540 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:46.271  2540  2540 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:46.271   871  1307 E native  : do suspend true
07-26 15:23:46.273  2540  2540 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:23:46.273  2540  2540 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:23:46.273  2540  2677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:46.273  2540  2677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:46.273  2540  2677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:46.273  2540  2560 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
07-26 15:23:46.273  2540  2560 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
07-26 15:23:46.274  2540  2540 D HidService: Received stop request...Stopping profile...
07-26 15:23:46.274  2540  2540 D HidService: Stopping Bluetooth HidService
07-26 15:23:46.274  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:46.274  1353  1353 D BluetoothInputDevice: Proxy object disconnected
07-26 15:23:46.274  1353  1353 D HidProfile: Bluetooth service disconnected
07-26 15:23:46.275  2540  2540 D HealthService: Received stop request...Stopping profile...
07-26 15:23:46.277  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.277  2540  2540 D PanService: Received stop request...Stopping profile...
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:46.278  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:46.278  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.278  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:46.279  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-26 15:23:46.279  1353  1353 D PanProfile: Bluetooth service disconnected
07-26 15:23:46.280  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:46.281  2540  2540 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:23:46.281  2540  2540 D BluetoothMapService: stop()
07-26 15:23:46.281  2540  2540 D BluetoothMapAppObserver: deinitObservers()
07-26 15:23:46.282  2540  2540 D BluetoothMapAppObserver: removeReceiver()
07-26 15:23:46.282   871  1949 D DhcpClient: Clearing IP address
07-26 15:23:46.283  1353  1353 D BluetoothMap: Proxy object disconnected
07-26 15:23:46.283  1353  1353 D MapProfile: Bluetooth service disconnected
07-26 15:23:46.283   372   869 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:23:46.283  2540  2540 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:46.283  2540  2540 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:46.283  2540  2540 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:46.283  2540  2540 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:46.285   372   869 D CommandListener: Setting iface cfg
07-26 15:23:46.285  2540  2677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:46.285  2540  2560 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-26 15:23:46.285  2540  2677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:46.285  2540  2677 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:23:46.285  2540  2677 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:23:46.285  2540  2677 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:23:46.285  2540  2677 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:23:46.286  2540  2540 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:46.286  2540  2540 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:46.286  2540  2540 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:46.286  2540  2540 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:46.286  1537  2307 V NativeCrypto: Read error: ssl=0xacc0f600: I/O error during system call, Connection timed out
07-26 15:23:46.286  2540  2540 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:23:46.286  2540  2560 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-26 15:23:46.287  2540  2540 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:23:46.287  2540  2540 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:46.287  2540  2540 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:46.287  2540  2540 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:46.288  2540  2540 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:46.288  2540  2540 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:23:46.288  2540  2560 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
07-26 15:23:46.289   871  1307 D WifiStateMachine: Start Disconnecting Watchdog 1
07-26 15:23:46.290  1537  2307 V NativeCrypto: SSL shutdown failed: ssl=0xacc0f600: I/O error during system call, Broken pipe
07-26 15:23:46.290   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:23:46.290   871  1307 E native  : do suspend true
07-26 15:23:46.291   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-26 15:23:46.291   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
07-26 15:23:46.294   398   398 E Parcel  : Reading a NULL string not supported here.
07-26 15:23:46.294   871  1950 D DhcpClient: Receive thread stopped
07-26 15:23:46.296  2540  2540 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-26 15:23:46.296  2540  2540 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:46.296  2540  2540 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:46.296  2540  2540 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:46.296  2540  2540 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:46.297  2540  2540 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-26 15:23:46.297  2540  2540 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:23:46.298  2540  2540 D BluetoothMapService: MAP Service closeService in
07-26 15:23:46.298  2540  2540 D BluetoothMapMasInstance0: MAP Service shutdown
07-26 15:23:46.298  2540  2540 D ObexServerSockets0: shutdown(block = true)
07-26 15:23:46.298  2540  2750 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
07-26 15:23:46.299  2540  2540 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:23:46.299  2540  2751 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-26 15:23:46.300  2540  2717 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-26 15:23:46.300  2540  2540 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:23:46.300  2540  2540 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:46.300  2540  2540 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:46.300  2540  2540 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:46.300  2540  2540 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:46.301   372   869 D CommandListener: Clearing all IP addresses on wlan0
07-26 15:23:46.301  2540  2556 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-26 15:23:46.301  2540  2540 D BluetoothMapService: cleanup()
07-26 15:23:46.301  2540  2556 D BluetoothAdapterProperties: Setting state to 15
07-26 15:23:46.301  2540  2556 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-26 15:23:46.301  2540  2540 D BluetoothMapService: MAP Service closeService in
,07-26 15:23:46.301  2540  2556 I BluetoothAdapterState: Entering BleOnState
07-26 15:23:46.303   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:23:46.303  1353  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:23:46.304  2540  2540 I BtOppRfcommListener: stopping Accept Thread
07-26 15:23:46.304  2540  3297 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:23:46.305  2540  3297 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:23:46.307  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:46.307  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:46.308  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.308  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:46.310  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:46.310  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:46.311  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.311  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:46.315   871   884 I ActivityManager: Start proc 3823:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
07-26 15:23:46.316   871  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-26 15:23:46.317   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:46.318  1353  1365 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:23:46.319   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:23:46.319  1353  1821 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:23:46.319   871  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
07-26 15:23:46.322   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:46.323  1353  1364 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:23:46.324  1353  1365 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:23:46.325  1353  1364 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:23:46.326  1737  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:46.326  2540  2556 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-26 15:23:46.326  2540  2556 D BluetoothAdapterProperties: Setting state to 16
07-26 15:23:46.326  2540  2556 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
,07-26 15:23:46.327  2540  2556 D BluetoothAdapterProperties: onBleDisable
07-26 15:23:46.327  2540  2556 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:23:46.328  2540  2557 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-26 15:23:46.329  2540  2560 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:23:46.331  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:46.331  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:46.332  2540  2677 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-26 15:23:46.332  2540  2677 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:46.332  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:46.332  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:23:46.334  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:46.335  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:46.339   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
07-26 15:23:46.342   871  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-26 15:23:46.346  2019  2175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-26 15:23:46.346  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:46.346  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:46.347  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.347  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:46.349  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:46.349  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:23:46.349  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:46.350  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:46.356   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:23:46.368  3823  3823 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm
,07-26 15:23:46.378  3823  3823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:23:46.384  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:23:46.386   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d18bccc:true
,07-26 15:23:46.388   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:23:46.389   871  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,07-26 15:23:46.389   871  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:23:46.401   871   881 I ActivityManager: Start proc 3839:com.google.android.apps.maps/u0a65 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,07-26 15:23:46.407   871   888 D Tethering: MasterInitialState.processMessage what=3
,07-26 15:23:46.414  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:46.415  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:46.434  3823  3823 D LocalBluetoothProfileManager: Adding local MAP profile
,07-26 15:23:46.436  3823  3823 D BluetoothMap: Create BluetoothMap proxy object
,07-26 15:23:46.448  3839  3839 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm
,07-26 15:23:46.450  3823  3823 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,07-26 15:23:46.460  3823  3823 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:23:46.464   871  1381 I ActivityManager: Killing 2847:com.google.android.calendar/u0a37 (adj 15): empty #17
07-26 15:23:46.465   372   869 E Netd    : netlink response contains error (No such file or directory)
,07-26 15:23:46.539  2540  2560 I bt_hci  : shut_down
,07-26 15:23:46.539  2540  2566 D bt_hwcfg: hw_epilog_process
,07-26 15:23:46.543  2540  2566 I bt_vendor: low_power_mode_cb
,07-26 15:23:46.565  2540  2566 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-26 15:23:46.565  2540  2566 I bt_vendor: epilog_cb
07-26 15:23:46.565  2540  2566 I bt_hci  : epilog_finished_callback
,07-26 15:23:46.570  2540  2560 I bt_hci_h4: hal_close
,07-26 15:23:46.571  2540  2560 I bt_userial_vendor: device fd = 51 close
,07-26 15:23:46.615  3839  3839 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.io.File.exists(File.java:361)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.615  3839  3839 D StrictMode: StrictMode policy violation; ~duration=71 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.615  3839  3839 D StrictMode: StrictMode policy violation; ~duration=70 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.615  3839  3839 D StrictMode: StrictMode policy violation; ~duration=69 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.r.e.b(PG:170)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.615  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.616  3839  3839 D StrictMode: StrictMode policy violation; ~duration=65 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.r.k.d(PG:1187)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.r.k.c(PG:18147)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.r.k.d(PG:583)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.r.v.a(PG:1161)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.r.y.a(PG:2188)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.r.e.b(PG:170)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.r.e.b(PG:15188)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.616  3839  3839 D StrictMode: StrictMode policy violation; ~duration=55 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.File.exists(File.java:361)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.616  3839  3839 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.File.doAccess(File.java:281)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.File.exists(File.java:361)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.616  3839  3839 D StrictMode: StrictMode policy violation; ~duration=54 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.io.File.lastModified(File.java:569)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:23:46.616  3839  3839 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:23:46.621  3823  3823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:23:46.633  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:23:46.642  3823  3823 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:23:46.688   871  1412 I ActivityManager: Start proc 3874:com.google.android.talk/u0a61 for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver
07-26 15:23:46.692   871  1412 I ActivityManager: Killing 3504:com.google.android.deskclock/u0a44 (adj 15): empty #17
,07-26 15:23:46.802  2540  2557 D bt_stack_manager: event_shut_down_stack finished.
,07-26 15:23:46.802  2540  2556 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-26 15:23:46.810  2540  2540 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-26 15:23:46.810  2540  2556 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-26 15:23:46.811  2540  2540 D BtGatt.GattService: Received stop request...Stopping profile...
07-26 15:23:46.811  2540  2540 D BtGatt.GattService: stop()
,07-26 15:23:46.811  2540  2540 D BtGatt.AdvertiseManager: advertise clients cleared
,07-26 15:23:46.812  2540  2540 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:23:46.812  2540  2540 V BluetoothAdapterState: isTurningOn()=false
,07-26 15:23:46.812  2540  2540 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:46.812  2540  2540 V BluetoothAdapterState: isBleTurningOff()=true
,07-26 15:23:46.813  2540  2556 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-26 15:23:46.813  2540  2556 D BluetoothAdapterProperties: Setting state to 10
,07-26 15:23:46.814  2540  2556 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-26 15:23:46.814   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
07-26 15:23:46.815  2540  2556 I BluetoothAdapterState: Entering OffState
,07-26 15:23:46.821  2540  2540 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
07-26 15:23:46.821  2540  2540 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-26 15:23:46.821  2540  2540 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-26 15:23:46.821  2540  2557 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
07-26 15:23:46.824  2540  2557 D bt_stack_manager: event_clean_up_stack finished.
,07-26 15:23:46.825  3874  3874 W System  : ClassLoader referenced unknown path: /system/app/Hangouts/lib/arm
,07-26 15:23:46.837  2540  2540 I art     : System.exit called, status: 0
,07-26 15:23:46.837  2540  2540 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-26 15:23:46.879   871  1675 I ActivityManager: Process com.android.bluetooth (pid 2540) has died
,07-26 15:23:46.962  3839  3868 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,07-26 15:23:47.053  3874  3895 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
,07-26 15:23:47.053  3874  3895 I Babel_SMS: MmsConfig.loadMmsSettings
,07-26 15:23:47.054  3874  3895 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
07-26 15:23:47.054  3874  3895 I Babel_SMS: MmsConfig.loadFromDatabase
,07-26 15:23:47.086  3874  3895 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
,07-26 15:23:47.086  3874  3895 I Babel_SMS: MmsConfig.loadFromResources
,07-26 15:23:47.088  3874  3895 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
,07-26 15:23:47.089  3874  3895 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=nexus6, mUaProfUrl=http://uaprof.motorola.com/phoneconfig/nexus6/Profile/nexus6.rdf
,07-26 15:23:47.124  3874  3874 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:23:47.127  3874  3874 I Babel_Crash: startup - clean
,07-26 15:23:47.147  3874  3874 I Babel_telephony: TeleModule.launchCompleted
,07-26 15:23:47.160   871  1381 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-26 15:23:47.181  3874  3874 I Babel_telephony: TeleModule.updateConnectionManagerRegistration, registration preference changed from false to false
,07-26 15:23:47.191   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5da0ad:true
,07-26 15:23:47.192  3874  3874 W Babel   : BAM#gBA: invalid account id: -1
,07-26 15:23:47.192  3874  3874 W Babel   : BAM#gBA: invalid account id: -1
07-26 15:23:47.193  3874  3874 I Babel_telephony: TeleModule.updateIncomingCallRegistration, preferred account for incoming calls changed from: null to null
,07-26 15:23:47.203  3874  3900 I Babel   : deleted: false for 0
,07-26 15:23:47.206   871  1417 I Telecom : PhoneAccountRegistrar: SimCallManager queried, returning: null
,07-26 15:23:47.269   871  1412 I ActivityManager: Start proc 3902:com.google.android.apps.gcs/u0a89 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,07-26 15:23:47.279  3874  3874 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:23:47.330  3874  3874 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-26 15:23:47.352  3874  3874 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:23:47.364  3874  3874 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:23:47.366  3902  3902 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-26 15:23:47.368  3874  3874 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:23:47.391  3874  3874 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-26 15:23:47.406  3874  3874 I vclib   : onServiceConnected
,07-26 15:23:47.464  3902  3902 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-26 15:23:47.508   871  1381 I ActivityManager: Killing 3522:com.qualcomm.timeservice/1000 (adj 15): empty #17
,07-26 15:23:47.571  2061  2061 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-26 15:23:47.575  2061  2061 D SystemUpdateService: onCreate
,07-26 15:23:47.578  2061  2061 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-26 15:23:47.599  2061  3926 I SystemUpdateService: active receiver: enabled
,07-26 15:23:47.601  2061  2061 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-26 15:23:47.607  2061  2349 I iu.UploadsManager: num queued entries: 0
07-26 15:23:47.608  2061  2349 I iu.UploadsManager: num updated entries: 0
,07-26 15:23:47.616  2061  3926 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-26 15:23:47.620  2061  3926 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-26 15:23:47.620  2061  3926 I SystemUpdateService: now status is 0 (complete)
,07-26 15:23:47.622  2061  2061 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:23:47.621  2061  3926 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-26 15:23:47.623  2061  3926 I SystemUpdateService: file has been verified
,07-26 15:23:47.625  2061  2349 I iu.SyncManager: NEXT; no task
,07-26 15:23:47.625  2061  2061 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-26 15:23:47.626  2061  3926 I SystemUpdateService: OTA package size = 12249756
,07-26 15:23:47.640  2061  3926 I SystemUpdateService: showing system update notification
07-26 15:23:47.644   871   881 I ActivityManager: Start proc 3928:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
07-26 15:23:47.655  2061  2061 D SystemUpdateService: onDestroy
07-26 15:23:47.679  3928  3928 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm
07-26 15:23:47.682  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
07-26 15:23:47.687  3928  3928 D SprintDMHelper: simOperator: 
07-26 15:23:47.690  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-26 15:23:47.707   871   881 I ActivityManager: Start proc 3940:com.android.chrome/u0a40 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
07-26 15:23:47.709   871   881 I ActivityManager: Killing 3310:com.android.providers.calendar/u0a3 (adj 15): empty #17
,07-26 15:23:47.839   871  1412 I ActivityManager: Start proc 3955:com.google.android.apps.magazines/u0a67 for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider
,07-26 15:23:47.843  3874  3954 I Babel   : connection state changed from UNKNOWN to DISCONNECTED
,07-26 15:23:47.850   871  1417 I ActivityManager: Killing 3359:android.process.acore/u0a5 (adj 15): empty #17,
,07-26 15:23:47.922  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/Newsstand/lib/arm
,07-26 15:23:47.985  3955  3955 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
07-26 15:23:47.985  3955  3955 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
07-26 15:23:47.985  3955  3955 I GAv4    :   adb logcat -s GAv4
,07-26 15:23:48.002  3955  3955 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:23:48.010  3955  3955 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:23:48.030  3955  3973 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,07-26 15:23:48.147  3955  3955 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
,07-26 15:23:48.188  3955  3955 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,07-26 15:23:48.201  3955  3955 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5092-5094)
,07-26 15:23:48.201  3955  3955 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-26 15:23:48.211  3955  3955 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b04d42e}
,07-26 15:23:48.212  3955  3955 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-26 15:23:48.212  3955  3955 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,07-26 15:23:48.221  3955  3955 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-26 15:23:48.224  3955  3955 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-26 15:23:48.242  3955  3955 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,07-26 15:23:48.258  3955  3955 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,07-26 15:23:48.258  3955  3955 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-26 15:23:48.258  3955  3955 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-26 15:23:48.258  3955  3955 I Adreno  : Build Date                       : 10/20/15
07-26 15:23:48.258  3955  3955 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-26 15:23:48.258  3955  3955 I Adreno  : Local Branch                     : M14
07-26 15:23:48.258  3955  3955 I Adreno  : Remote Branch                    : 
07-26 15:23:48.258  3955  3955 I Adreno  : Remote Branch                    : 
07-26 15:23:48.258  3955  3955 I Adreno  : Reconstruct Branch               : 
,07-26 15:23:48.323  3955  3955 I NSApplication: Starting up...
,07-26 15:23:48.332  3955  4001 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-26 15:23:48.364   871  2152 I ActivityManager: Start proc 4006:com.google.android.apps.photos/u0a71 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,07-26 15:23:48.366   871  2152 I ActivityManager: Killing 3581:com.google.android.partnersetup/u0a16 (adj 15): empty #17
,07-26 15:23:48.443  4006  4006 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,07-26 15:23:48.626   871  2848 I ActivityManager: Killing 3597:com.android.musicfx/u0a18 (adj 15): empty #17
,07-26 15:23:49.274   871  2848 D WifiService: setWifiEnabled: true pid=3761, uid=10000
,07-26 15:23:49.275   871  2848 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:23:49.292   871  1307 D WifiConfigStore: Loading config and enabling all networks 
,07-26 15:23:49.297  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:49.297  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:49.297  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:23:49.297  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:23:49.299  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:49.299  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:23:49.299  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:49.299  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:23:49.326   871  1307 D WifiConfigStore: loaded 0 passpoint configs
,07-26 15:23:49.326   871  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-26 15:23:49.327   871  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-26 15:23:49.327   871  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,07-26 15:23:49.328   871  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,07-26 15:23:49.328   871  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
07-26 15:23:49.329   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
,07-26 15:23:49.329   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-26 15:23:49.343   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-26 15:23:49.344   871  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
07-26 15:23:49.345   372   869 D CommandListener: Setting iface cfg
,07-26 15:23:49.351   871  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '59 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 59 Failed to set address (No such device)'
,07-26 15:23:49.351   871  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-26 15:23:49.354   871  1307 E native  : do suspend true
,07-26 15:23:49.357   871  1306 D WifiNative-HAL: p2pGetDeviceAddress
,07-26 15:23:49.361   871  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
,07-26 15:23:49.368   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:23:50.636   871  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-26 15:23:50.711   871  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=7.88 rxSuccessRate=23.31 delta 1000 -> 994
,07-26 15:23:50.713   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
,07-26 15:23:50.713   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:23:50.734   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-26 15:23:50.793   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-26 15:23:50.796  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-26 15:23:51.219  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,07-26 15:23:51.256  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,07-26 15:23:51.258  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-26 15:23:51.268   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:23:51.275   871  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-26 15:23:51.276   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-26 15:23:51.276   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:23:51.294   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:23:51.310   372   869 D CommandListener: Setting iface cfg
,07-26 15:23:51.311   871  1307 D WifiStateMachine: Start Dhcp Watchdog 2
,07-26 15:23:51.323   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-26 15:23:51.374   871  4031 D DhcpClient: Receive thread started
,07-26 15:23:51.459   871  1307 E native  : do suspend false
,07-26 15:23:51.477   871  1949 D DhcpClient: Broadcasting DHCPDISCOVER
,07-26 15:23:51.489   871  4031 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172495, domain null
,07-26 15:23:51.490   871  1949 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172495 seconds
,07-26 15:23:51.492   871  1949 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
,07-26 15:23:51.505   871  4031 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-26 15:23:51.506   871  1949 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-26 15:23:51.507   372   869 D CommandListener: Setting iface cfg
,07-26 15:23:51.517   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,07-26 15:23:51.517   871  1949 D DhcpClient: Scheduling renewal in 86399s
07-26 15:23:51.519   871  1307 E native  : do suspend true
,07-26 15:23:51.541   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,07-26 15:23:51.544   871  1307 D WifiConfigStore: No blacklist allowed without epno enabled
07-26 15:23:51.545   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,07-26 15:23:51.547   871  1309 D ConnectivityService: Adding iface wlan0 to network 101
,07-26 15:23:51.554   871  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-26 15:23:51.621   871  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
,07-26 15:23:51.622   871  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,07-26 15:23:51.625   871  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,07-26 15:23:51.628   871  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,07-26 15:23:51.630   871  1309 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,07-26 15:23:51.644   871  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,07-26 15:23:51.650   871  1309 D ConnectivityService: scheduleUnvalidatedPrompt 101
,07-26 15:23:51.650   871  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
07-26 15:23:51.650   871  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,07-26 15:23:51.650   871  1309 D ConnectivityService:    accepting network in place of null
07-26 15:23:51.650   871  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,07-26 15:23:51.651   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-26 15:23:51.652   871  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-26 15:23:51.700   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:23:51.761   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:23:51.771   871  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,07-26 15:23:51.772   871  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:23:51.780   871  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,07-26 15:23:51.781   871   888 D Tethering: MasterInitialState.processMessage what=3
,07-26 15:23:51.794  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:51.794  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:51.794  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:51.795  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:23:51.798  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-26 15:23:51.798  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-26 15:23:51.798  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:23:51.798  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-26 15:23:51.808  2061  2061 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-26 15:23:51.811  2061  2061 D SystemUpdateService: onCreate
,07-26 15:23:51.814  2061  2061 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-26 15:23:51.817  2061  4043 I SystemUpdateService: active receiver: enabled
,07-26 15:23:51.824  2061  4043 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-26 15:23:51.826  2061  4043 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-26 15:23:51.827  2061  4043 I SystemUpdateService: now status is 0 (complete)
,07-26 15:23:51.827  2061  4043 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-26 15:23:51.827  2061  4043 I SystemUpdateService: file has been verified
07-26 15:23:51.827  2061  4043 I SystemUpdateService: OTA package size = 12249756
,07-26 15:23:51.834  2061  4043 I SystemUpdateService: showing system update notification
,07-26 15:23:51.838  2061  2061 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-26 15:23:51.840  2061  2349 I iu.UploadsManager: num queued entries: 0
07-26 15:23:51.841  2061  2349 I iu.UploadsManager: num updated entries: 0
,07-26 15:23:51.842  2061  2349 I iu.SyncManager: NEXT; no task
07-26 15:23:51.843  2061  2061 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:23:51.845  2061  2061 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
07-26 15:23:51.845  2061  4046 I MDM     : [232] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-26 15:23:51.845  2061  4046 W BaseAppContext: Using Auth Proxy for data requests.
07-26 15:23:51.847  2061  4046 V GoogleAuthProtoRequest: [232] a.<init>: mAccountName set to: thalitester@gmail.com
,07-26 15:23:51.847  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:23:51.851  2061  2061 D SystemUpdateService: onDestroy
07-26 15:23:51.851  3928  3928 D SprintDMHelper: simOperator: 
,07-26 15:23:51.851  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-26 15:23:51.860  1537  1537 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:23:51.862  1537  1537 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:23:51.888  1537  1945 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
07-26 15:23:51.888  1537  1945 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-26 15:23:51.888  1537  1945 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-26 15:23:51.888  1537  1945 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-26 15:23:51.901  3874  3874 I art     : Waiting for a blocking GC DisableMovingGc
,07-26 15:23:51.903  2061  4046 E MDM     : [232] SitrepService.a: Error sending sitrep.
,07-26 15:23:51.905  3874  3874 I art     : Starting a blocking GC DisableMovingGc
,07-26 15:23:52.283   871  2303 D WifiService: setWifiEnabled: false pid=3761, uid=10000
,07-26 15:23:52.284   871  2303 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:23:52.322  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,07-26 15:23:52.328   871  1307 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-26 15:23:52.329   871  1307 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
07-26 15:23:52.329   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:23:52.330   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:23:52.358   871  1307 E native  : do suspend true
,07-26 15:23:52.374   871  1949 D DhcpClient: Clearing IP address
07-26 15:23:52.374   372   869 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:23:52.378   372   869 D CommandListener: Setting iface cfg
,07-26 15:23:52.393   871  4031 D DhcpClient: Receive thread stopped
,07-26 15:23:52.395   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
07-26 15:23:52.395   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,07-26 15:23:52.399   871  1307 D WifiStateMachine: Start Disconnecting Watchdog 2
,07-26 15:23:52.403   398   398 E Parcel  : Reading a NULL string not supported here.
,07-26 15:23:52.405   871  1309 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
07-26 15:23:52.411   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
07-26 15:23:52.411   871  1307 E native  : do suspend true
,07-26 15:23:52.453   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:23:52.475   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:23:52.475   871  1309 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
07-26 15:23:52.476   871  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:23:52.476   372   869 D CommandListener: Clearing all IP addresses on wlan0
,07-26 15:23:52.479   871   888 D Tethering: MasterInitialState.processMessage what=3
,07-26 15:23:52.482  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:52.482  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:52.482  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:52.482  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:52.483   871  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-26 15:23:52.483  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:52.483  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:52.483  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:52.484  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:23:52.493  2061  2061 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-26 15:23:52.498  2061  2061 D SystemUpdateService: onCreate
,07-26 15:23:52.501   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:23:52.504  2019  2175 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-26 15:23:52.504  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:52.504  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:52.504  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:52.505  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:52.505   871  1307 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-26 15:23:52.506  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:52.506  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:52.506  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:23:52.506  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:23:52.512  2061  2061 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-26 15:23:52.516  2061  4060 I SystemUpdateService: active receiver: enabled
,07-26 15:23:52.520  2061  2061 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-26 15:23:52.527  2061  2349 I iu.UploadsManager: num queued entries: 0
,07-26 15:23:52.527  2061  2349 I iu.UploadsManager: num updated entries: 0
07-26 15:23:52.528  2061  2349 I iu.SyncManager: NEXT; no task
,07-26 15:23:52.529  2061  4060 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-26 15:23:52.531  2061  2061 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:23:52.532  2061  2061 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-26 15:23:52.533  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:23:52.537  3928  3928 D SprintDMHelper: simOperator: 
07-26 15:23:52.537  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-26 15:23:52.539  2061  4060 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,07-26 15:23:52.539  2061  4060 I SystemUpdateService: now status is 0 (complete)
07-26 15:23:52.539  2061  4060 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,07-26 15:23:52.540  2061  4060 I SystemUpdateService: file has been verified
,07-26 15:23:52.540  2061  4060 I SystemUpdateService: OTA package size = 12249756
,07-26 15:23:52.565   372   869 E Netd    : netlink response contains error (No such file or directory)
,07-26 15:23:52.566   871  1309 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,07-26 15:23:52.578  2061  4060 I SystemUpdateService: showing system update notification
,07-26 15:23:52.588  2061  2061 D SystemUpdateService: onDestroy
,07-26 15:23:52.770   871  1309 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,07-26 15:23:55.342   871   888 I ActivityManager: Start proc 4069:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-26 15:23:55.470  4069  4069 D AdapterServiceConfig: Adding HeadsetService
,07-26 15:23:55.471  4069  4069 D AdapterServiceConfig: Adding A2dpService
07-26 15:23:55.472  4069  4069 D AdapterServiceConfig: Adding HidService
,07-26 15:23:55.472  4069  4069 D AdapterServiceConfig: Adding HealthService
07-26 15:23:55.473  4069  4069 D AdapterServiceConfig: Adding PanService
,07-26 15:23:55.474  4069  4069 D AdapterServiceConfig: Adding GattService
,07-26 15:23:55.475  4069  4069 D AdapterServiceConfig: Adding BluetoothMapService
,07-26 15:23:55.499  4069  4069 D BluetoothAdapterState: make() - Creating AdapterState
07-26 15:23:55.499   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5eee77:true
,07-26 15:23:55.504  4069  4069 I bt_bluedroid: init
,07-26 15:23:55.505  4069  4081 I BluetoothAdapterState: Entering OffState
,07-26 15:23:55.511  4069  4082 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-26 15:23:55.511  4069  4082 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-26 15:23:55.511  4069  4082 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-26 15:23:55.512  4069  4082 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-26 15:23:55.514  4069  4069 I bt_bluedroid: get_profile_interface socket
,07-26 15:23:55.516  4069  4069 I bt_bluedroid: get_profile_interface sdp
,07-26 15:23:55.519  4069  4085 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-26 15:23:55.519  4069  4080 I bt_bluedroid: config_hci_snoop_log
,07-26 15:23:55.523   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,07-26 15:23:55.524  4069  4085 D BluetoothAdapterProperties: Name is: Nexus 6
,07-26 15:23:55.532  4069  4081 D BluetoothAdapterState: Current state: OFF, message: 0
,07-26 15:23:55.533  4069  4081 D BluetoothAdapterProperties: Setting state to 14
07-26 15:23:55.533  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-26 15:23:55.537  4069  4081 D BluetoothBondStateMachine: make
,07-26 15:23:55.542  4069  4086 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-26 15:23:55.548  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:23:55.549  4069  4069 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-26 15:23:55.553  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
07-26 15:23:55.553  4069  4069 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-26 15:23:55.554  4069  4069 D BtGatt.GattService: Received start request. Starting profile...
07-26 15:23:55.554  4069  4069 D BtGatt.GattService: start()
,07-26 15:23:55.554  4069  4069 I bt_bluedroid: get_profile_interface gatt
07-26 15:23:55.555  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:23:55.555  4069  4069 D BtGatt.AdvertiseManager: advertise manager created
,07-26 15:23:55.565  4069  4069 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:23:55.565  4069  4069 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:55.565  4069  4069 V BluetoothAdapterState: isBleTurningOn()=true
,07-26 15:23:55.565  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:23:55.566  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4,
07-26 15:23:55.567  4069  4081 I bt_bluedroid: enable
07-26 15:23:55.567  4069  4082 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-26 15:23:55.568  4069  4082 I bt_hci  : start_up
,07-26 15:23:55.578  4069  4082 I bt_vendor: alloc value 0xb3a88189
,07-26 15:23:55.578  4069  4082 I bt_vendor: init
07-26 15:23:55.578  4069  4082 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-26 15:23:55.578  4069  4082 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-26 15:23:55.684  4069  4082 D bt_hci  : start_up starting async portion
,07-26 15:23:55.684  4069  4089 I bt_hci  : event_finish_startup
07-26 15:23:55.685  4069  4089 I bt_hci_h4: hal_open
07-26 15:23:55.685  4069  4089 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-26 15:23:55.696  4069  4089 I bt_userial_vendor: device fd = 51 open
,07-26 15:23:55.726  4069  4089 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-26 15:23:55.758  4069  4089 D bt_hwcfg: Chipset BCM4354A2
,07-26 15:23:55.759  4069  4089 D bt_hwcfg: Target name = [BCM4354A2]
,07-26 15:23:55.760  4069  4089 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-26 15:23:56.417  4069  4089 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-26 15:23:56.418  4069  4089 D bt_hwcfg: Settlement delay -- 100 ms
07-26 15:23:56.419  4069  4089 I bt_hwcfg: Setting fw settlement delay to 100 
,07-26 15:23:56.535  4069  4089 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-26 15:23:56.537  4069  4089 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-26 15:23:56.565  4069  4089 I bt_hwcfg: vendor lib fwcfg completed
,07-26 15:23:56.566  4069  4089 I bt_vendor: firmware callback
07-26 15:23:56.566  4069  4089 I bt_hci  : firmware_config_callback
,07-26 15:23:56.578  4069  4091 I bt_btu  : btu_task pending for preload complete event
,07-26 15:23:56.579  4069  4091 I bt_btu_task: Bluetooth chip preload is complete
07-26 15:23:56.579  4069  4091 I bt_btu  : btu_task received preload complete event
,07-26 15:23:56.589  4069  4091 I         : BTE_InitTraceLevels -- TRC_HCI
07-26 15:23:56.589  4069  4091 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-26 15:23:56.589  4069  4091 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-26 15:23:56.590  4069  4091 I         : BTE_InitTraceLevels -- TRC_AVDT
07-26 15:23:56.590  4069  4091 I         : BTE_InitTraceLevels -- TRC_AVRC
07-26 15:23:56.590  4069  4091 I         : BTE_InitTraceLevels -- TRC_A2D
,07-26 15:23:56.591  4069  4091 I         : BTE_InitTraceLevels -- TRC_BNEP
07-26 15:23:56.591  4069  4091 I         : BTE_InitTraceLevels -- TRC_BTM
,07-26 15:23:56.591  4069  4091 I         : BTE_InitTraceLevels -- TRC_GAP
07-26 15:23:56.591  4069  4091 I         : BTE_InitTraceLevels -- TRC_PAN
,07-26 15:23:56.591  4069  4091 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:23:56.592  4069  4091 I         : BTE_InitTraceLevels -- TRC_GATT
,07-26 15:23:56.592  4069  4091 I         : BTE_InitTraceLevels -- TRC_SMP
07-26 15:23:56.592  4069  4091 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-26 15:23:56.593  4069  4091 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-26 15:23:56.667   871  4029 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,07-26 15:23:56.669   871  1309 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,07-26 15:23:56.726  4069  4091 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a05d9d
,07-26 15:23:56.727  4069  4091 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a05d9d 
,07-26 15:23:56.741  4069  4085 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-26 15:23:56.742  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-26 15:23:56.743  4069  4085 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-26 15:23:56.749  4069  4085 D BluetoothAdapterProperties: Name is: Nexus 6
,07-26 15:23:56.753  4069  4085 D BluetoothAdapterProperties: Scan Mode:20
,07-26 15:23:56.754  4069  4085 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-26 15:23:56.755  4069  4085 D bt_hci  : do_postload posting postload work item
,07-26 15:23:56.755  4069  4089 I bt_hci  : event_postload
,07-26 15:23:56.756  4069  4089 I bt_vendor: sco_config_cb
07-26 15:23:56.756  4069  4089 I bt_hci  : sco_config_callback postload finished.
,07-26 15:23:56.759  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:56.760  4069  4085 D bt_bte_conf: Device ID record 1 : primary
,07-26 15:23:56.760  4069  4085 D bt_bte_conf:   vendorId            = 000f
07-26 15:23:56.761  4069  4085 D bt_bte_conf:   vendorIdSource      = 0001
07-26 15:23:56.761  4069  4085 D bt_bte_conf:   product             = 1200
07-26 15:23:56.761  4069  4085 D bt_bte_conf:   version             = 1436
07-26 15:23:56.761  4069  4085 D bt_bte_conf:   clientExecutableURL = 
07-26 15:23:56.762  4069  4085 D bt_bte_conf:   serviceDescription  = 
,07-26 15:23:56.762  4069  4085 D bt_bte_conf:   documentationURL    = 
07-26 15:23:56.762  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:56.762  4069  4085 D bt_bte_conf: bte_load_did_conf no section named DID2.
07-26 15:23:56.763  4069  4082 D bt_stack_manager: event_start_up_stack finished
07-26 15:23:56.763  4069  4089 I bt_vendor: low_power_mode_cb
07-26 15:23:56.764  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
07-26 15:23:56.764  4069  4081 D BluetoothAdapterProperties: Setting state to 15
,07-26 15:23:56.764  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-26 15:23:56.766  4069  4081 I BluetoothAdapterState: Entering BleOnState
,07-26 15:23:56.773  4069  4081 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-26 15:23:56.774  4069  4081 D BluetoothAdapterProperties: Setting state to 11
07-26 15:23:56.774  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,07-26 15:23:56.784  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:56.786  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:56.789  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:23:56.790  4069  4069 D HeadsetService: Received start request. Starting profile...
,07-26 15:23:56.793  4069  4069 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-26 15:23:56.793  4069  4069 D HeadsetStateMachine: make
,07-26 15:23:56.804  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:23:56.804  4069  4069 D HeadsetStateMachine: max_hf_connections = 1
07-26 15:23:56.804  4069  4069 I bt_bluedroid: get_profile_interface handsfree
,07-26 15:23:56.804  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-26 15:23:56.804  4069  4085 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-26 15:23:56.811  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:23:56.811  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
07-26 15:23:56.811  4069  4069 D A2dpService: Received start request. Starting profile...
,07-26 15:23:56.812  4069  4069 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-26 15:23:56.813  4069  4069 I bt_bluedroid: get_profile_interface avrcp
,07-26 15:23:56.820  4069  4069 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-26 15:23:56.820  4069  4069 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:23:56.820  4069  4069 D A2dpStateMachine: make
,07-26 15:23:56.822  4069  4069 I bt_bluedroid: get_profile_interface a2dp
,07-26 15:23:56.823  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-26 15:23:56.824  4069  4099 D A2dpStateMachine: Enter Disconnected: -2
,07-26 15:23:56.824  4069  4069 I BluetoothHidServiceJni: classInitNative: succeeds
,07-26 15:23:56.825  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:23:56.827  4069  4069 D HidService: Received start request. Starting profile...
,07-26 15:23:56.827  3823  3823 D BluetoothInputDevice: Proxy object connected
,07-26 15:23:56.827  4069  4069 I bt_bluedroid: get_profile_interface hidhost
07-26 15:23:56.827  4069  4085 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e73e5
07-26 15:23:56.827  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-26 15:23:56.827  4069  4069 D HidService: setHidService(): set to: null
07-26 15:23:56.828  4069  4069 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-26 15:23:56.829  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
07-26 15:23:56.829  3823  3823 D HidProfile: Bluetooth service connected
07-26 15:23:56.830  4069  4069 D HealthService: Received start request. Starting profile...
,07-26 15:23:56.833  4069  4069 I bt_bluedroid: get_profile_interface health
,07-26 15:23:56.835  4069  4069 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-26 15:23:56.835  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:23:56.837  4069  4069 D PanService: Received start request. Starting profile...
,07-26 15:23:56.837  3823  3823 D BluetoothPan: BluetoothPAN Proxy object connected
,07-26 15:23:56.837  4069  4069 D BluetoothPanServiceJni: initializeNative(L110): pan,
07-26 15:23:56.837  4069  4069 I bt_bluedroid: get_profile_interface pan
07-26 15:23:56.838  4069  4085 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-26 15:23:56.838  3823  3823 D PanProfile: Bluetooth service connected
,07-26 15:23:56.840  4069  4069 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:23:56.841  4069  4069 D BluetoothMapService: Received start request. Starting profile...
,07-26 15:23:56.842  4069  4069 D BluetoothMapService: start()
07-26 15:23:56.842  3823  3823 D BluetoothMap: Proxy object connected
07-26 15:23:56.842  3823  3823 D MapProfile: Bluetooth service connected
,07-26 15:23:56.843  3823  3823 D BluetoothMap: getConnectedDevices()
,07-26 15:23:56.849  3823  3823 D BluetoothMap: Bluetooth is Not enabled
,07-26 15:23:56.857  4069  4069 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-26 15:23:56.858  4069  4069 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER,
07-26 15:23:56.858  4069  4069 D BluetoothMapAppObserver: createReceiver()
,07-26 15:23:56.859  4069  4069 D BluetoothMapAppObserver: initObservers()
07-26 15:23:56.859  4069  4069 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-26 15:23:56.867  4069  4097 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-26 15:23:56.867  4069  4069 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:23:56.867  4069  4069 V BluetoothAdapterState: isTurningOn()=true,
07-26 15:23:56.867  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:56.867  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:23:56.871  4069  4069 V BluetoothAdapterState: isTurningOff()=false
07-26 15:23:56.871  4069  4069 V BluetoothAdapterState: isTurningOn()=true
07-26 15:23:56.871  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:56.871  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isTurningOff()=false
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isTurningOn()=true
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isTurningOff()=false
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isTurningOn()=true
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:56.872  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isTurningOff()=false
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isTurningOn()=true
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isTurningOff()=false
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isTurningOn()=true
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:56.873  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:56.874  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-26 15:23:56.874  4069  4081 D BluetoothAdapterProperties: ScanMode =  20
07-26 15:23:56.874  4069  4081 D BluetoothAdapterProperties: State =  11
07-26 15:23:56.874  4069  4081 D BluetoothAdapterProperties: Setting state to 12
07-26 15:23:56.874  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-26 15:23:56.876   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:23:56.876  4069  4085 D BluetoothAdapterProperties: Scan Mode:21
,07-26 15:23:56.877  4069  4085 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:23:56.877  4069  4081 I BluetoothAdapterState: Entering OnState
07-26 15:23:56.877  1353  1365 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-26 15:23:56.880   871   871 D BluetoothA2dp: Proxy object connected
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:56.881  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:56.884  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:56.885  1353  1353 D BluetoothA2dp: Proxy object connected
,07-26 15:23:56.886  4069  4069 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:23:56.886  4069  4069 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-26 15:23:56.888  4069  4069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:56.888  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:23:56.888   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:23:56.889  1353  1820 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:23:56.890   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:23:56.890  1353  1364 D BluetoothMap: onBluetoothStateChange: up=true
,07-26 15:23:56.892   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:23:56.892  1353  1365 D BluetoothPan: onBluetoothStateChange on: true
,07-26 15:23:56.892  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:56.892  1353  1353 D BluetoothMap: Proxy object connected
07-26 15:23:56.892  1353  1353 D MapProfile: Bluetooth service connected
07-26 15:23:56.892  1353  1353 D BluetoothMap: getConnectedDevices()
07-26 15:23:56.894  1353  1364 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:23:56.895  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
,07-26 15:23:56.895  4069  4069 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:23:56.895  1353  1353 D PanProfile: Bluetooth service connected
07-26 15:23:56.896  3823  3834 D BluetoothPan: onBluetoothStateChange on: true
,07-26 15:23:56.896  1353  1821 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 15:23:56.897  4069  4069 D ObexServerSockets: Succeed to create listening sockets 
07-26 15:23:56.897  4069  4069 D ObexServerSockets0: startAccept()
,07-26 15:23:56.897  4069  4069 D ObexServerSockets0: prepareForNewConnect()
07-26 15:23:56.898  1353  1353 D BluetoothInputDevice: Proxy object connected
07-26 15:23:56.898  1353  1353 D HidProfile: Bluetooth service connected
07-26 15:23:56.898  3823  3835 D BluetoothMap: onBluetoothStateChange: up=true
,07-26 15:23:56.901  3823  3834 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:23:56.902  1737  1858 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:23:56.902  4069  4069 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
07-26 15:23:56.902  4069  4069 D BluetoothSdpJni: SDP Create record success - handle: 0
07-26 15:23:56.903  3823  3835 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-26 15:23:56.903  4069  4106 D ObexServerSockets0: Accepting socket connection...
07-26 15:23:56.904   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
07-26 15:23:56.905  4069  4069 D BluetoothMapService: onReceive
,07-26 15:23:56.905  4069  4069 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:23:56.905  4069  4069 D BluetoothMapService: STATE_ON
07-26 15:23:56.907  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:56.908  3823  3823 D LocalBluetoothProfileManager: Adding local A2DP profile
07-26 15:23:56.907  4069  4107 D ObexServerSockets0: Accepting socket connection...
07-26 15:23:56.909  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:56.919  3823  3823 D LocalBluetoothProfileManager: Adding local HEADSET profile
,07-26 15:23:56.925  3823  3823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:23:56.926  4069  4069 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:23:56.926  4069  4069 D ObexServerSockets0: prepareForNewConnect()
07-26 15:23:56.927  3823  3823 D BluetoothA2dp: Proxy object connected
,07-26 15:23:56.932  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
07-26 15:23:56.933  3874  4048 W Babel_NetworkConnectionCheckingService: IO exceptions, probably not a captive portal 
07-26 15:23:56.934  3874  4048 I Babel   : connection state changed from DISCONNECTED to CONNECTED
07-26 15:23:56.936  1353  1353 D BluetoothPbap: Proxy object connected
,07-26 15:23:56.936  1353  1353 D PbapServerProfile: Bluetooth service connected
,07-26 15:23:56.938  4069  4108 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:23:56.939  3874  4048 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,07-26 15:23:56.950  3823  3823 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:23:56.951  3823  3823 D BluetoothPbap: Proxy object connected
,07-26 15:23:56.951  3823  3823 D PbapServerProfile: Bluetooth service connected
,07-26 15:23:56.952   871  1381 I ActivityManager: Killing 2124:com.google.android.gms.wearable/u0a11 (adj 15): empty #17
,07-26 15:23:57.009   871   871 D BluetoothHeadset: Proxy object connected
,07-26 15:23:57.009  4069  4115 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:23:57.011  1737  1763 D BluetoothHeadset: Proxy object connected
,07-26 15:23:57.011  4069  4115 I BtOppRfcommListener: Accept thread started.
07-26 15:23:57.011   871   871 D BluetoothHeadset: Proxy object connected
07-26 15:23:57.012   871   871 D BluetoothHeadset: Proxy object connected
07-26 15:23:57.012  1353  1821 D BluetoothHeadset: Proxy object connected
07-26 15:23:57.013  1353  1353 D HeadsetProfile: Bluetooth service connected
,07-26 15:23:57.023  3823  3835 D BluetoothHeadset: Proxy object connected
,07-26 15:23:57.025  3823  3823 D HeadsetProfile: Bluetooth service connected
,07-26 15:23:58.305  4069  4081 D BluetoothAdapterState: Current state: ON, message: 23
,07-26 15:23:58.305  4069  4081 D BluetoothAdapterProperties: Setting state to 13
,07-26 15:23:58.305  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-26 15:23:58.307  4069  4081 D BluetoothAdapterProperties: onBluetoothDisable()
,07-26 15:23:58.312  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:23:58.319  4069  4069 D BluetoothMapService: onReceive
,07-26 15:23:58.319  4069  4069 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,07-26 15:23:58.320  4069  4069 D BluetoothMapService: STATE_TURNING_OFF
07-26 15:23:58.320  4069  4069 D BluetoothMapService: MAP Service closeService in
,07-26 15:23:58.321  4069  4069 D BluetoothMapMasInstance0: MAP Service shutdown
,07-26 15:23:58.321  4069  4069 D ObexServerSockets0: shutdown(block = true)
,07-26 15:23:58.322  4069  4106 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,07-26 15:23:58.323  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:58.323  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:23:58.326  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-26 15:23:58.327  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:23:58.331  4069  4069 D ObexServerSockets0: shutdown called from another thread - interrupt().
07-26 15:23:58.331  4069  4085 D BluetoothAdapterProperties: Scan Mode:20
,07-26 15:23:58.332  4069  4093 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
07-26 15:23:58.333  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
07-26 15:23:58.333  4069  4069 D ObexServerSockets0: shutdown called from another thread - interrupt().
,07-26 15:23:58.332  4069  4107 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
07-26 15:23:58.336  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:23:58.336  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:23:58.335  3823  3823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:23:58.336  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-26 15:23:58.337  4069  4069 D HeadsetService: Received stop request...Stopping profile...
,07-26 15:23:58.337  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:23:58.338  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:58.341  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:58.342  3823  3835 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:58.342   871   871 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:58.342  1737  1753 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:58.343   871   871 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:58.343   871   871 D BluetoothHeadset: Proxy object disconnected
07-26 15:23:58.343  1353  1821 D BluetoothHeadset: Proxy object disconnected
,07-26 15:23:58.344  4069  4069 I BtOppRfcommListener: stopping Accept Thread
07-26 15:23:58.344  1353  1353 D HeadsetProfile: Bluetooth service disconnected
07-26 15:23:58.344  4069  4115 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-26 15:23:58.344  4069  4115 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-26 15:23:58.347  4069  4069 D A2dpService: Received stop request...Stopping profile...
07-26 15:23:58.347  4069  4099 D A2dpStateMachine: Exit Disconnected: -1
,07-26 15:23:58.349   871   871 D BluetoothA2dp: Proxy object disconnected
07-26 15:23:58.349  1353  1353 D BluetoothA2dp: Proxy object disconnected
,07-26 15:23:58.350  4069  4069 D HidService: Received stop request...Stopping profile...
07-26 15:23:58.350  4069  4069 D HidService: Stopping Bluetooth HidService
,07-26 15:23:58.351  4069  4069 D HealthService: Received stop request...Stopping profile...
,07-26 15:23:58.351  1353  1353 D BluetoothInputDevice: Proxy object disconnected
07-26 15:23:58.352  1353  1353 D HidProfile: Bluetooth service disconnected
07-26 15:23:58.352  4069  4069 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:58.353  4069  4069 V BluetoothAdapterState: isTurningOn()=false
,07-26 15:23:58.353  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:58.353  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:23:58.354  3823  3823 D DockEventReceiver: finishStartingService: stopping service
07-26 15:23:58.354  4069  4069 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-26 15:23:58.355  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,07-26 15:23:58.355  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:58.355  4069  4069 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-26 15:23:58.355  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:58.355  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:58.355  4069  4085 E bt_btif : btif_hf_upstreams_evt: Invalid index 65534
,07-26 15:23:58.356  4069  4069 D PanService: Received stop request...Stopping profile...
,07-26 15:23:58.357  1353  1353 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-26 15:23:58.357  1353  1353 D PanProfile: Bluetooth service disconnected
07-26 15:23:58.357  4069  4069 D BluetoothMapService: Received stop request...Stopping profile...
07-26 15:23:58.357  4069  4069 D BluetoothMapService: stop()
,07-26 15:23:58.358  4069  4069 D BluetoothMapAppObserver: deinitObservers()
07-26 15:23:58.358  4069  4069 D BluetoothMapAppObserver: removeReceiver()
,07-26 15:23:58.358  3823  3823 D HeadsetProfile: Bluetooth service disconnected
,07-26 15:23:58.359  3823  3823 D BluetoothA2dp: Proxy object disconnected
07-26 15:23:58.359  1353  1353 D BluetoothMap: Proxy object disconnected
07-26 15:23:58.359  1353  1353 D MapProfile: Bluetooth service disconnected
07-26 15:23:58.360  3823  3823 D BluetoothInputDevice: Proxy object disconnected
07-26 15:23:58.360  3823  3823 D HidProfile: Bluetooth service disconnected
07-26 15:23:58.361  3823  3823 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-26 15:23:58.361  3823  3823 D PanProfile: Bluetooth service disconnected
07-26 15:23:58.361  3823  3823 D BluetoothMap: Proxy object disconnected
07-26 15:23:58.361  3823  3823 D MapProfile: Bluetooth service disconnected
07-26 15:23:58.362  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:23:58.366  4069  4069 V BluetoothAdapterState: isTurningOff()=true
,07-26 15:23:58.366  4069  4069 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:58.366  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:58.366  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:23:58.367  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
07-26 15:23:58.367  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:58.367  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:58.368  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-26 15:23:58.368  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:23:58.368  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-26 15:23:58.368  4069  4091 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-26 15:23:58.368  4069  4069 V BluetoothAdapterState: isTurningOff()=true
07-26 15:23:58.368  4069  4069 V BluetoothAdapterState: isTurningOn()=false
,07-26 15:23:58.368  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:58.368  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:23:58.368  4069  4069 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-26 15:23:58.368  4069  4085 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
07-26 15:23:58.369  4069  4069 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-26 15:23:58.369  4069  4069 V BluetoothAdapterState: isTurningOff()=true
,07-26 15:23:58.369  4069  4069 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:58.369  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:58.369  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:58.370  4069  4069 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-26 15:23:58.370  4069  4085 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,07-26 15:23:58.370  4069  4069 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-26 15:23:58.370  4069  4069 V BluetoothAdapterState: isTurningOff()=true
,07-26 15:23:58.370  4069  4069 V BluetoothAdapterState: isTurningOn()=false
,07-26 15:23:58.371  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:23:58.371  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:58.371  4069  4069 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,07-26 15:23:58.371  4069  4069 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-26 15:23:58.372  4069  4069 D BluetoothMapService: MAP Service closeService in
,07-26 15:23:58.372  4069  4069 V BluetoothAdapterState: isTurningOff()=true
,07-26 15:23:58.372  4069  4069 V BluetoothAdapterState: isTurningOn()=false
,07-26 15:23:58.372  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:23:58.372  4069  4069 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:23:58.373  4069  4069 D BluetoothMapService: cleanup()
,07-26 15:23:58.373  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
07-26 15:23:58.373  4069  4069 D BluetoothMapService: MAP Service closeService in
07-26 15:23:58.373  4069  4081 D BluetoothAdapterProperties: Setting state to 15
07-26 15:23:58.373  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
07-26 15:23:58.375  4069  4081 I BluetoothAdapterState: Entering BleOnState
07-26 15:23:58.375   871   888 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-26 15:23:58.375  1353  1353 D BluetoothPbap: Proxy object disconnected
07-26 15:23:58.375  1353  1364 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:23:58.375  1353  1353 D PbapServerProfile: Bluetooth service disconnected
07-26 15:23:58.376   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:58.376  3823  3823 D BluetoothPbap: Proxy object disconnected
,07-26 15:23:58.376  1353  1821 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:58.376  3823  3823 D PbapServerProfile: Bluetooth service disconnected
07-26 15:23:58.376   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:58.377  3823  3834 D BluetoothA2dp: onBluetoothStateChange: up=false
07-26 15:23:58.379  1353  1365 D BluetoothMap: onBluetoothStateChange: up=false
,07-26 15:23:58.380   871   888 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:58.380  1353  1820 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:23:58.380  1353  1364 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:23:58.382  3823  3835 D BluetoothPan: onBluetoothStateChange on: false
07-26 15:23:58.383  1353  1821 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:23:58.384  3823  3834 D BluetoothMap: onBluetoothStateChange: up=false
07-26 15:23:58.385  3823  3835 D BluetoothHeadset: onBluetoothStateChange: up=false
07-26 15:23:58.385  3823  3834 D BluetoothPbap: onBluetoothStateChange: up=false
07-26 15:23:58.386  1737  1869 D BluetoothHeadset: onBluetoothStateChange: up=false
,07-26 15:23:58.386  3823  3835 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-26 15:23:58.387  4069  4081 D BluetoothAdapterState: Current state: BLE ON, message: 20
07-26 15:23:58.388  4069  4081 D BluetoothAdapterProperties: Setting state to 16
07-26 15:23:58.388  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
07-26 15:23:58.388  4069  4081 D BluetoothAdapterProperties: onBleDisable
07-26 15:23:58.389  4069  4082 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
07-26 15:23:58.390  4069  4091 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,07-26 15:23:58.390  4069  4091 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
07-26 15:23:58.391  4069  4081 I BluetoothAdapterState: Entering PendingCommandState
07-26 15:23:58.393  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:23:58.396  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:58.397  4069  4085 D BluetoothAdapterProperties: Scan Mode:20
07-26 15:23:58.397  3823  3823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:23:58.399  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:58.400  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:23:58.403  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:23:58.407  3823  3823 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:23:58.591  4069  4085 I bt_hci  : shut_down
,07-26 15:23:58.603  4069  4089 D bt_hwcfg: hw_epilog_process
,07-26 15:23:58.603  4069  4089 I bt_vendor: low_power_mode_cb
,07-26 15:23:58.621  4069  4089 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,07-26 15:23:58.621  4069  4089 I bt_vendor: epilog_cb
07-26 15:23:58.622  4069  4089 I bt_hci  : epilog_finished_callback
,07-26 15:23:58.629  4069  4085 I bt_hci_h4: hal_close
,07-26 15:23:58.631  4069  4085 I bt_userial_vendor: device fd = 51 close
,07-26 15:23:58.761  4069  4082 D bt_stack_manager: event_shut_down_stack finished.
,07-26 15:23:58.762  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,07-26 15:23:58.767  4069  4081 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,07-26 15:23:58.768  4069  4069 D BtGatt.DebugUtils: handleDebugAction() action=null
07-26 15:23:58.769  4069  4069 D BtGatt.GattService: Received stop request...Stopping profile...
,07-26 15:23:58.769  4069  4069 D BtGatt.GattService: stop()
07-26 15:23:58.770  4069  4069 D BtGatt.AdvertiseManager: advertise clients cleared
,07-26 15:23:58.775  4069  4069 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:23:58.775  4069  4069 V BluetoothAdapterState: isTurningOn()=false
07-26 15:23:58.776  4069  4069 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:23:58.776  4069  4069 V BluetoothAdapterState: isBleTurningOff()=true
07-26 15:23:58.777  4069  4081 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,07-26 15:23:58.779  4069  4081 D BluetoothAdapterProperties: Setting state to 10
07-26 15:23:58.779  4069  4081 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
07-26 15:23:58.781  4069  4081 I BluetoothAdapterState: Entering OffState
,07-26 15:23:58.783   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,07-26 15:23:58.815  4069  4069 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,07-26 15:23:58.815  4069  4069 W BluetoothSdpJni: Cleaning up Bluetooth Health object
07-26 15:23:58.816  4069  4082 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,07-26 15:23:58.826  4069  4082 D bt_stack_manager: event_clean_up_stack finished.
,07-26 15:23:58.827  4069  4069 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-26 15:23:58.836  4069  4069 I art     : System.exit called, status: 0
,07-26 15:23:58.836  4069  4069 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-26 15:23:58.880   871  1675 I ActivityManager: Process com.android.bluetooth (pid 4069) has died
,07-26 15:23:59.654   871  1309 D ConnectivityService: handlePromptUnvalidated 101
,07-26 15:24:01.301  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:24:01.302  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:24:04.310  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:24:04.311  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b6dbc66 added. We now have 6 listener(s)
07-26 15:24:04.311  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:24:04.315  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:04.316  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a047ba7 added. We now have 7 listener(s)
,07-26 15:24:04.316  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:24:04.318  3761  3809 I System.out: IsBluetoothEnabled
,07-26 15:24:04.328  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:04.366   871   888 I ActivityManager: Start proc 4127:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,07-26 15:24:04.498  4127  4127 D AdapterServiceConfig: Adding HeadsetService
,07-26 15:24:04.499  4127  4127 D AdapterServiceConfig: Adding A2dpService
07-26 15:24:04.499  4127  4127 D AdapterServiceConfig: Adding HidService
,07-26 15:24:04.499  4127  4127 D AdapterServiceConfig: Adding HealthService
,07-26 15:24:04.499  4127  4127 D AdapterServiceConfig: Adding PanService
07-26 15:24:04.500  4127  4127 D AdapterServiceConfig: Adding GattService
07-26 15:24:04.500  4127  4127 D AdapterServiceConfig: Adding BluetoothMapService
,07-26 15:24:04.515   871   888 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8f987f8:true
,07-26 15:24:04.516  4127  4127 D BluetoothAdapterState: make() - Creating AdapterState
,07-26 15:24:04.521  4127  4127 I bt_bluedroid: init
,07-26 15:24:04.521  4127  4139 I BluetoothAdapterState: Entering OffState
,07-26 15:24:04.527  4127  4140 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,07-26 15:24:04.527  4127  4140 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-26 15:24:04.528  4127  4140 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-26 15:24:04.528  4127  4140 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-26 15:24:04.530  4127  4127 I bt_bluedroid: get_profile_interface socket
,07-26 15:24:04.532  4127  4127 I bt_bluedroid: get_profile_interface sdp
,07-26 15:24:04.536  4127  4138 I bt_bluedroid: config_hci_snoop_log
,07-26 15:24:04.538   871   888 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
07-26 15:24:04.538  4127  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-26 15:24:04.544  4127  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,07-26 15:24:04.547  4127  4139 D BluetoothAdapterState: Current state: OFF, message: 0
,07-26 15:24:04.548  4127  4139 D BluetoothAdapterProperties: Setting state to 14
07-26 15:24:04.548  4127  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,07-26 15:24:04.552  4127  4139 D BluetoothBondStateMachine: make
,07-26 15:24:04.556  4127  4144 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-26 15:24:04.562  4127  4139 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:24:04.563  4127  4127 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,07-26 15:24:04.567  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:04.568  4127  4127 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-26 15:24:04.569  4127  4127 D BtGatt.GattService: Received start request. Starting profile...
,07-26 15:24:04.569  4127  4127 D BtGatt.GattService: start()
07-26 15:24:04.569  4127  4127 I bt_bluedroid: get_profile_interface gatt
,07-26 15:24:04.570  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:04.570  4127  4127 D BtGatt.AdvertiseManager: advertise manager created
,07-26 15:24:04.580  4127  4127 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:24:04.580  4127  4127 V BluetoothAdapterState: isTurningOn()=false
07-26 15:24:04.580  4127  4127 V BluetoothAdapterState: isBleTurningOn()=true
,07-26 15:24:04.580  4127  4127 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:24:04.581  4127  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
07-26 15:24:04.581  4127  4139 I bt_bluedroid: enable
07-26 15:24:04.582  4127  4140 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,07-26 15:24:04.583  4127  4140 I bt_hci  : start_up
,07-26 15:24:04.603  4127  4140 I bt_vendor: alloc value 0xb3a88189
,07-26 15:24:04.604  4127  4140 I bt_vendor: init
07-26 15:24:04.604  4127  4140 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
,07-26 15:24:04.604  4127  4140 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,07-26 15:24:04.713  4127  4140 D bt_hci  : start_up starting async portion
07-26 15:24:04.714  4127  4147 I bt_hci  : event_finish_startup
07-26 15:24:04.714  4127  4147 I bt_hci_h4: hal_open
07-26 15:24:04.714  4127  4147 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-26 15:24:04.722  4127  4147 I bt_userial_vendor: device fd = 51 open
,07-26 15:24:04.756  4127  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-26 15:24:04.788  4127  4147 D bt_hwcfg: Chipset BCM4354A2
,07-26 15:24:04.789  4127  4147 D bt_hwcfg: Target name = [BCM4354A2]
,07-26 15:24:04.790  4127  4147 I bt_hwcfg: Found patchfile: /vendor/firmware//bcm4354A2.hcd
,07-26 15:24:05.072  1537  1537 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:24:05.087  1537  1537 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:24:05.091  1537  1537 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-26 15:24:05.144  1537  1912 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-26 15:24:05.144  1537  1912 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-26 15:24:05.145  1537  1912 I GLSUser : [GLSUser] Extracting token using key: Auth,
07-26 15:24:05.145  1537  1912 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-26 15:24:05.181  1537  1912 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-26 15:24:05.181  1537  1912 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-26 15:24:05.181  1537  1912 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-26 15:24:05.181  1537  1912 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-26 15:24:05.181  1537  1912 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-26 15:24:05.181  1537  1912 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-26 15:24:05.181  1537  1912 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-26 15:24:05.193  3377  3407 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-26 15:24:05.193  3377  3407 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-26 15:24:05.193  3377  3407 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-26 15:24:05.193  3377  3407 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-26 15:24:05.193  3377  3407 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-26 15:24:05.193  3377  3407 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-26 15:24:05.193  3377  3407 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-26 15:24:05.390  4127  4147 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-26 15:24:05.391  4127  4147 D bt_hwcfg: Settlement delay -- 100 ms
,07-26 15:24:05.391  4127  4147 I bt_hwcfg: Setting fw settlement delay to 100 
,07-26 15:24:05.508  4127  4147 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-26 15:24:05.509  4127  4147 I bt_hwcfg: Setting local bd addr to F8:CF:C5:D9:E5:61
,07-26 15:24:05.539  4127  4147 I bt_hwcfg: vendor lib fwcfg completed
07-26 15:24:05.539  4127  4147 I bt_vendor: firmware callback
,07-26 15:24:05.540  4127  4147 I bt_hci  : firmware_config_callback
,07-26 15:24:05.551  4127  4150 I bt_btu  : btu_task pending for preload complete event
07-26 15:24:05.551  4127  4150 I bt_btu_task: Bluetooth chip preload is complete
07-26 15:24:05.551  4127  4150 I bt_btu  : btu_task received preload complete event
,07-26 15:24:05.562  4127  4150 I         : BTE_InitTraceLevels -- TRC_HCI
07-26 15:24:05.562  4127  4150 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-26 15:24:05.562  4127  4150 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-26 15:24:05.563  4127  4150 I         : BTE_InitTraceLevels -- TRC_AVDT
07-26 15:24:05.563  4127  4150 I         : BTE_InitTraceLevels -- TRC_AVRC
07-26 15:24:05.563  4127  4150 I         : BTE_InitTraceLevels -- TRC_A2D
,07-26 15:24:05.563  4127  4150 I         : BTE_InitTraceLevels -- TRC_BNEP
07-26 15:24:05.564  4127  4150 I         : BTE_InitTraceLevels -- TRC_BTM
,07-26 15:24:05.564  4127  4150 I         : BTE_InitTraceLevels -- TRC_GAP
07-26 15:24:05.564  4127  4150 I         : BTE_InitTraceLevels -- TRC_PAN
,07-26 15:24:05.565  4127  4150 I         : BTE_InitTraceLevels -- TRC_SDP
07-26 15:24:05.565  4127  4150 I         : BTE_InitTraceLevels -- TRC_GATT
07-26 15:24:05.565  4127  4150 I         : BTE_InitTraceLevels -- TRC_SMP
,07-26 15:24:05.565  4127  4150 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-26 15:24:05.566  4127  4150 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-26 15:24:05.697  4127  4150 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xb3a05d9d
,07-26 15:24:05.697  4127  4150 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xb3a05d9d 
,07-26 15:24:05.710  4127  4143 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 1024 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 10 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,07-26 15:24:05.711  4127  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,07-26 15:24:05.712  4127  4143 D BluetoothAdapterProperties: Address is:F8:CF:C5:D9:E5:61
,07-26 15:24:05.716  4127  4143 D BluetoothAdapterProperties: Name is: Nexus 6
,07-26 15:24:05.720  4127  4143 D BluetoothAdapterProperties: Scan Mode:20
,07-26 15:24:05.720  4127  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-26 15:24:05.721  4127  4143 D bt_hci  : do_postload posting postload work item
,07-26 15:24:05.721  4127  4147 I bt_hci  : event_postload
07-26 15:24:05.721  4127  4147 I bt_vendor: sco_config_cb
07-26 15:24:05.721  4127  4147 I bt_hci  : sco_config_callback postload finished.
07-26 15:24:05.724  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:05.726  4127  4143 D bt_bte_conf: Device ID record 1 : primary
07-26 15:24:05.726  4127  4143 D bt_bte_conf:   vendorId            = 000f
07-26 15:24:05.726  4127  4143 D bt_bte_conf:   vendorIdSource      = 0001
07-26 15:24:05.726  4127  4143 D bt_bte_conf:   product             = 1200
07-26 15:24:05.726  4127  4143 D bt_bte_conf:   version             = 1436
07-26 15:24:05.727  4127  4143 D bt_bte_conf:   clientExecutableURL = 
07-26 15:24:05.727  4127  4143 D bt_bte_conf:   serviceDescription  = 
07-26 15:24:05.727  4127  4143 D bt_bte_conf:   documentationURL    = 
07-26 15:24:05.727  4127  4143 D bt_bte_conf: bte_load_did_conf no section named DID2.
,07-26 15:24:05.728  4127  4140 D bt_stack_manager: event_start_up_stack finished
,07-26 15:24:05.729  4127  4147 I bt_vendor: low_power_mode_cb
07-26 15:24:05.729  4127  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,07-26 15:24:05.730  4127  4139 D BluetoothAdapterProperties: Setting state to 15
,07-26 15:24:05.730  4127  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
07-26 15:24:05.731  4127  4139 I BluetoothAdapterState: Entering BleOnState
,07-26 15:24:05.736  4127  4139 D BluetoothAdapterState: Current state: BLE ON, message: 1
07-26 15:24:05.737  4127  4139 D BluetoothAdapterProperties: Setting state to 11
07-26 15:24:05.737  4127  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
07-26 15:24:05.744  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:05.752  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:05.753  4127  4127 D HeadsetService: Received start request. Starting profile...
,07-26 15:24:05.759  4127  4127 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-26 15:24:05.759  4127  4127 D HeadsetStateMachine: make
,07-26 15:24:05.764  4127  4139 I BluetoothAdapterState: Entering PendingCommandState
,07-26 15:24:05.768  4127  4127 D HeadsetStateMachine: max_hf_connections = 1
07-26 15:24:05.768  4127  4127 I bt_bluedroid: get_profile_interface handsfree
07-26 15:24:05.769  4127  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
07-26 15:24:05.769  4127  4143 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,07-26 15:24:05.773  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:24:05.774  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
07-26 15:24:05.774  4127  4127 D A2dpService: Received start request. Starting profile...
,07-26 15:24:05.775  4127  4127 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-26 15:24:05.775  4127  4127 I bt_bluedroid: get_profile_interface avrcp
,07-26 15:24:05.781  4127  4127 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-26 15:24:05.781  4127  4127 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-26 15:24:05.781  4127  4127 D A2dpStateMachine: make
,07-26 15:24:05.782  4127  4127 I bt_bluedroid: get_profile_interface a2dp
,07-26 15:24:05.783  4127  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,07-26 15:24:05.784  4127  4159 D A2dpStateMachine: Enter Disconnected: -2
,07-26 15:24:05.786  4127  4127 I BluetoothHidServiceJni: classInitNative: succeeds
,07-26 15:24:05.786  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:05.787  4127  4127 D HidService: Received start request. Starting profile...
07-26 15:24:05.787  4127  4127 I bt_bluedroid: get_profile_interface hidhost
07-26 15:24:05.787  4127  4127 D HidService: setHidService(): set to: null
,07-26 15:24:05.787  4127  4143 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xb39e73e5
07-26 15:24:05.788  4127  4143 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
07-26 15:24:05.788  4127  4127 I BluetoothHealthServiceJni: classInitNative: succeeds
07-26 15:24:05.789  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:05.790  4127  4127 D HealthService: Received start request. Starting profile...
,07-26 15:24:05.791  4127  4127 I bt_bluedroid: get_profile_interface health
,07-26 15:24:05.792  4127  4127 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-26 15:24:05.793  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:05.793  4127  4127 D PanService: Received start request. Starting profile...
,07-26 15:24:05.794  4127  4127 D BluetoothPanServiceJni: initializeNative(L110): pan
07-26 15:24:05.794  4127  4127 I bt_bluedroid: get_profile_interface pan
07-26 15:24:05.794  4127  4143 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-26 15:24:05.796  4127  4127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:05.797  4127  4127 D BluetoothMapService: Received start request. Starting profile...
07-26 15:24:05.797  4127  4127 D BluetoothMapService: start()
,07-26 15:24:05.799  4127  4127 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,07-26 15:24:05.800  4127  4127 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
07-26 15:24:05.800  4127  4127 D BluetoothMapAppObserver: createReceiver()
,07-26 15:24:05.800  4127  4127 D BluetoothMapAppObserver: initObservers()
07-26 15:24:05.801  4127  4127 D BluetoothMapAppObserver: getEnabledAccountItems()
,07-26 15:24:05.807  4127  4127 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:24:05.808  4127  4127 V BluetoothAdapterState: isTurningOn()=true
07-26 15:24:05.808  4127  4127 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:24:05.808  4127  4127 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:24:05.810  4127  4157 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-26 15:24:05.811  4127  4127 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:24:05.811  4127  4127 V BluetoothAdapterState: isTurningOn()=true
07-26 15:24:05.811  4127  4127 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:24:05.811  4127  4127 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:24:05.811  4127  4127 V BluetoothAdapterState: isTurningOff()=false
07-26 15:24:05.811  4127  4127 V BluetoothAdapterState: isTurningOn()=true
07-26 15:24:05.812  4127  4127 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:24:05.812  4127  4127 V BluetoothAdapterState: isBleTurningOff()=false
,07-26 15:24:05.812  4127  4127 V BluetoothAdapterState: isTurningOff()=false
07-26 15:24:05.812  4127  4127 V BluetoothAdapterState: isTurningOn()=true
07-26 15:24:05.813  4127  4127 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:24:05.813  4127  4127 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:24:05.813  4127  4127 V BluetoothAdapterState: isTurningOff()=false
07-26 15:24:05.813  4127  4127 V BluetoothAdapterState: isTurningOn()=true
07-26 15:24:05.813  4127  4127 V BluetoothAdapterState: isBleTurningOn()=false
,07-26 15:24:05.813  4127  4127 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:24:05.813  4127  4127 V BluetoothAdapterState: isTurningOff()=false
,07-26 15:24:05.814  4127  4127 V BluetoothAdapterState: isTurningOn()=true
07-26 15:24:05.814  4127  4127 V BluetoothAdapterState: isBleTurningOn()=false
07-26 15:24:05.814  4127  4127 V BluetoothAdapterState: isBleTurningOff()=false
07-26 15:24:05.814  4127  4139 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
07-26 15:24:05.815  4127  4139 D BluetoothAdapterProperties: ScanMode =  20
,07-26 15:24:05.815  4127  4139 D BluetoothAdapterProperties: State =  11
07-26 15:24:05.815  4127  4139 D BluetoothAdapterProperties: Setting state to 12
07-26 15:24:05.815  4127  4139 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
07-26 15:24:05.816   871   888 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:24:05.817  1353  1821 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:24:05.817  4127  4143 D BluetoothAdapterProperties: Scan Mode:21
07-26 15:24:05.817  4127  4139 I BluetoothAdapterState: Entering OnState
,07-26 15:24:05.817  4127  4143 D BluetoothAdapterProperties: Discoverable Timeout:120
07-26 15:24:05.818   871   871 D BluetoothA2dp: Proxy object connected
07-26 15:24:05.819  1353  1353 D BluetoothA2dp: Proxy object connected
07-26 15:24:05.819   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:24:05.820  1353  1820 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:24:05.821   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
,07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:05.821  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-26 15:24:05.821  3823  4119 D BluetoothA2dp: onBluetoothStateChange: up=true
07-26 15:24:05.823  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:24:05.825  1353  1365 D BluetoothMap: onBluetoothStateChange: up=true
,07-26 15:24:05.827  4127  4127 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
07-26 15:24:05.828  4127  4127 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
07-26 15:24:05.828   871   888 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:24:05.829  1353  1364 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:24:05.829  3823  3823 D BluetoothA2dp: Proxy object connected
07-26 15:24:05.830  4127  4127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-26 15:24:05.830  1353  1821 D BluetoothPbap: onBluetoothStateChange: up=true
07-26 15:24:05.832  4127  4127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:24:05.832  3823  3835 D BluetoothPan: onBluetoothStateChange on: true
07-26 15:24:05.833  4127  4127 D ObexServerSockets: Succeed to create listening sockets 
07-26 15:24:05.833  4127  4127 D ObexServerSockets0: startAccept()
07-26 15:24:05.834  4127  4127 D ObexServerSockets0: prepareForNewConnect()
,07-26 15:24:05.835  1353  1820 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 15:24:05.836  4127  4127 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,07-26 15:24:05.836  4127  4127 D BluetoothSdpJni: SDP Create record success - handle: 0
,07-26 15:24:05.837  3823  3834 D BluetoothMap: onBluetoothStateChange: up=true
,07-26 15:24:05.837  4127  4165 D ObexServerSockets0: Accepting socket connection...
07-26 15:24:05.838  1353  1353 D BluetoothMap: Proxy object connected
,07-26 15:24:05.838  1353  1353 D MapProfile: Bluetooth service connected
,07-26 15:24:05.838  1353  1353 D BluetoothMap: getConnectedDevices()
07-26 15:24:05.840  3823  3835 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:24:05.840  1353  1353 D BluetoothPan: BluetoothPAN Proxy object connected
,07-26 15:24:05.840  1353  1353 D PanProfile: Bluetooth service connected
07-26 15:24:05.840  3823  4119 D BluetoothPbap: onBluetoothStateChange: up=true
,07-26 15:24:05.840  1353  1353 D BluetoothInputDevice: Proxy object connected
,07-26 15:24:05.841  1353  1353 D HidProfile: Bluetooth service connected
07-26 15:24:05.841  4127  4166 D ObexServerSockets0: Accepting socket connection...
07-26 15:24:05.841  3823  3823 D BluetoothPan: BluetoothPAN Proxy object connected
07-26 15:24:05.841  3823  3823 D PanProfile: Bluetooth service connected
,07-26 15:24:05.842  3823  3823 D BluetoothMap: Proxy object connected
07-26 15:24:05.842  3823  3823 D MapProfile: Bluetooth service connected
,07-26 15:24:05.842  3823  3823 D BluetoothMap: getConnectedDevices()
07-26 15:24:05.842  1737  1869 D BluetoothHeadset: onBluetoothStateChange: up=true
07-26 15:24:05.843  3823  3834 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-26 15:24:05.844  3823  3823 D BluetoothInputDevice: Proxy object connected
07-26 15:24:05.844  3823  3823 D HidProfile: Bluetooth service connected
,07-26 15:24:05.845   871   871 I Telecom : BluetoothPhoneService: queryPhoneState
,07-26 15:24:05.847  4127  4127 D BluetoothMapService: onReceive
07-26 15:24:05.847  4127  4127 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
07-26 15:24:05.847  4127  4127 D BluetoothMapService: STATE_ON
07-26 15:24:05.848  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:24:05.855  3823  3823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-26 15:24:05.861  3823  3823 D DockEventReceiver: finishStartingService: stopping service
,07-26 15:24:05.862  1537  1537 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,07-26 15:24:05.873  3823  3823 D BluetoothPbap: Proxy object connected
,07-26 15:24:05.873  3823  3823 D PbapServerProfile: Bluetooth service connected
07-26 15:24:05.874  1353  1353 D BluetoothPbap: Proxy object connected
07-26 15:24:05.874  1353  1353 D PbapServerProfile: Bluetooth service connected
07-26 15:24:05.874  4127  4127 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,07-26 15:24:05.875  4127  4127 D ObexServerSockets0: prepareForNewConnect()
,07-26 15:24:05.887  4127  4171 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:24:05.913  4127  4175 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-26 15:24:05.915  4127  4175 I BtOppRfcommListener: Accept thread started.
,07-26 15:24:05.923  3823  3835 D BluetoothHeadset: Proxy object connected
,07-26 15:24:05.923   871   871 D BluetoothHeadset: Proxy object connected
,07-26 15:24:05.923  3823  3823 D HeadsetProfile: Bluetooth service connected
07-26 15:24:05.924  1737  1858 D BluetoothHeadset: Proxy object connected
07-26 15:24:05.925   871   871 D BluetoothHeadset: Proxy object connected
07-26 15:24:05.925   871   871 D BluetoothHeadset: Proxy object connected
,07-26 15:24:05.926  1353  1821 D BluetoothHeadset: Proxy object connected
,07-26 15:24:05.926  1353  1353 D HeadsetProfile: Bluetooth service connected
,07-26 15:24:05.928   871   888 D BluetoothHeadset: Proxy object connected
,07-26 15:24:05.940  3823  3834 D BluetoothHeadset: Proxy object connected
,07-26 15:24:05.941  3823  3823 D HeadsetProfile: Bluetooth service connected
,07-26 15:24:05.942  1737  1763 D BluetoothHeadset: Proxy object connected
,07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:06.351  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:06.358  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:24:06.361  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:24:06.362  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bbfb854 added. We now have 8 listener(s)
,07-26 15:24:06.362  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:24:06.368   871  2152 D WifiService: setWifiEnabled: false pid=3761, uid=10000
,07-26 15:24:06.368   871  2152 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:24:06.380  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:06.381   871   882 D WifiService: setWifiEnabled: true pid=3761, uid=10000
07-26 15:24:06.381   871   882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,07-26 15:24:06.393   871  1307 D WifiConfigStore: Loading config and enabling all networks 
,07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:06.413  3761  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:06.420  3761  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:24:06.428   871  1307 D WifiConfigStore: loaded 0 passpoint configs
,07-26 15:24:06.429   871  1307 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
07-26 15:24:06.429   871  1307 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,07-26 15:24:06.430   871  1307 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
07-26 15:24:06.431   871  1307 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
07-26 15:24:06.431   871  1307 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,07-26 15:24:06.431   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG7005g"WPA_PSK
07-26 15:24:06.431   871  1307 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,07-26 15:24:06.445   372   869 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,07-26 15:24:06.445   871  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-26 15:24:06.446   372   869 D CommandListener: Setting iface cfg
,07-26 15:24:06.446   871  1306 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '84 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 84 Failed to set address (No such device)'
07-26 15:24:06.446   871  1306 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-26 15:24:06.499   871  1306 D WifiNative-HAL: p2pGetDeviceAddress
,07-26 15:24:06.499   871  1306 D WifiNative-HAL: p2pGetDeviceAddress returning fa:cf:c5:d9:e5:62
07-26 15:24:06.501   871  1307 E native  : do suspend true
,07-26 15:24:06.546   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:07.404  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:07.413  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:24:07.426  3761  3809 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-26 15:24:07.428  3761  3809 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-26 15:24:07.434  3761  3809 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@b42a440 Bundle[{}]
,07-26 15:24:07.435  3761  3809 I io.jxcore.node.LifeCycleMonitor: start: OK
07-26 15:24:07.435  3761  3809 I io.jxcore.node.LifeCycleMonitor: stop: OK
07-26 15:24:07.436  3761  3809 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-26 15:24:07.437  3761  3809 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-26 15:24:07.438  3761  3809 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-26 15:24:07.439  3761  3809 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-26 15:24:07.445  3761  3809 I System.out: Running OutgoingSocketThread
,07-26 15:24:07.448  3761  4181 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 436)
,07-26 15:24:07.450  3761  4181 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44150
07-26 15:24:07.450  3761  4181 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-26 15:24:07.827   871  1307 D WifiConfigStore: Retrieve network priorities before PNO. Max priority: 2
,07-26 15:24:07.956   871  1307 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=8.31 rxSuccessRate=23.62 delta 1000 -> 994
,07-26 15:24:07.958   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=1 roam=3
07-26 15:24:07.959   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:24:07.974   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=1
,07-26 15:24:08.039   871  1307 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=1
,07-26 15:24:08.041  1457  1457 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,07-26 15:24:08.449  3761  3809 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 437)
,07-26 15:24:08.450  3761  3809 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 437)
,07-26 15:24:08.450  3761  3809 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 437)
07-26 15:24:08.451  3761  3809 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 437)
,07-26 15:24:08.464  3761  3809 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 442)
,07-26 15:24:08.464  3761  3809 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 442)
,07-26 15:24:08.465  3761  3809 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 442)
07-26 15:24:08.467  3761  3809 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 443)
,07-26 15:24:08.471  3761  3809 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 445)
,07-26 15:24:08.474  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:24:08.474  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc343fd added. We now have 2 listener(s)
,07-26 15:24:08.477  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-26 15:24:08.477  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:24:08.477  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:24:08.477  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:24:08.478  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78938f2 added. We now have 9 listener(s)
07-26 15:24:08.478  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:24:08.478  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:24:08.478  1457  1457 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
07-26 15:24:08.487  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:08.496  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:08.501  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:24:08.502  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:24:08.504  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:24:08.504  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a05c0 added. We now have 3 listener(s)
07-26 15:24:08.506  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:08.508  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-26 15:24:08.508  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:24:08.509  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:24:08.509  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:08.510  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:24:08.510  1457  1457 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-26 15:24:08.510  1457  1457 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=1 id_str=]
,07-26 15:24:08.510  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0522f9 added. We now have 10 listener(s)
,07-26 15:24:08.513  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:24:08.514  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:24:08.514  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:24:08.514  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:24:08.515  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:24:08.515  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.515  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:24:08.515  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.516  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fc343fd removed from the list
,07-26 15:24:08.516  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:24:08.516  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78938f2 removed from the list
07-26 15:24:08.516  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:24:08.517  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.517   871  1307 D WifiConfigStore: Retrieve network priorities after PNO.
,07-26 15:24:08.520  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.520  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.523  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:24:08.523  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:24:08.523  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.524  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@78938f2 not in the list
07-26 15:24:08.524  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:24:08.524  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:24:08.527  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:24:08.527  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:24:08.527  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.527  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f0522f9 removed from the list
,07-26 15:24:08.527  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:24:08.528  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.528  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:24:08.528  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.528  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@48a05c0 removed from the list
,07-26 15:24:08.528   871  1307 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-26 15:24:08.530  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:24:08.530  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6df23e added. We now have 2 listener(s)
07-26 15:24:08.531   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:24:08.531   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
07-26 15:24:08.532  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-26 15:24:08.532  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:24:08.533  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:24:08.533  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:08.533  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@793389f added. We now have 9 listener(s)
07-26 15:24:08.533  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:24:08.534  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:24:08.537  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:08.544  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:08.546  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:24:08.547  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:24:08.548  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:24:08.548  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ebf5b5 added. We now have 3 listener(s)
07-26 15:24:08.549  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:08.550  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:24:08.554   871  1307 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-26 15:24:08.556  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-26 15:24:08.556  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:24:08.556  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:24:08.556  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:08.556  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@552f44a added. We now have 10 listener(s)
,07-26 15:24:08.556  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:24:08.556  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:24:08.556  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:24:08.556  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:24:08.557  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-26 15:24:08.561  3761  3809 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:24:08.561  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:24:08.566  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-26 15:24:08.568  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:24:08.568  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:24:08.569   372   869 D CommandListener: Setting iface cfg
07-26 15:24:08.571   871  1307 D WifiStateMachine: Start Dhcp Watchdog 3
07-26 15:24:08.572  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
07-26 15:24:08.572  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 15:24:08.572  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
07-26 15:24:08.573  3761  3809 D BluetoothAdapter: STATE_ON
,07-26 15:24:08.575  4127  4156 D BtGatt.GattService: registerClient() - UUID=e8444cf8-cbef-4cef-bec6-a2f235b0438e
,07-26 15:24:08.577  4127  4143 D BtGatt.GattService: onClientRegistered() - UUID=e8444cf8-cbef-4cef-bec6-a2f235b0438e, clientIf=5
,07-26 15:24:08.578  3761  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
07-26 15:24:08.579  4127  4167 D BtGatt.GattService: start scan with filters
,07-26 15:24:08.581   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,07-26 15:24:08.582  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
07-26 15:24:08.582  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-26 15:24:08.583  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-26 15:24:08.583  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-26 15:24:08.585  4127  4146 D BtGatt.ScanManager: handling starting scan
,07-26 15:24:08.587  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
07-26 15:24:08.588  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
07-26 15:24:08.588  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-26 15:24:08.589  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
07-26 15:24:08.589  4127  4146 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@4b36ed4
,07-26 15:24:08.593  4127  4143 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-26 15:24:08.593  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.593  3761  3809 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,07-26 15:24:08.593  4127  4146 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-26 15:24:08.593  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:24:08.594  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:24:08.594  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 15:24:08.594  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-26 15:24:08.594  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...,
,07-26 15:24:08.594  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
,07-26 15:24:08.594  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-26 15:24:08.594  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:24:08.594  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,07-26 15:24:08.595  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:24:08.596  4127  4156 D BtGatt.GattService: stopScan() - queue size =1
,07-26 15:24:08.596  4127  4167 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 15:24:08.597  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:24:08.597  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,07-26 15:24:08.597  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-26 15:24:08.597  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-26 15:24:08.597  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,07-26 15:24:08.598  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-26 15:24:08.598  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-26 15:24:08.598  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,07-26 15:24:08.599  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-26 15:24:08.600  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:24:08.600  4127  4143 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-26 15:24:08.600  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.601  4127  4146 D BtGatt.ScanManager: Starting BLE batch scan
07-26 15:24:08.601  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-26 15:24:08.601  4127  4146 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-26 15:24:08.601  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:24:08.601  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:24:08.602  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:24:08.603  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:24:08.603  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:24:08.603  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:24:08.603  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.603  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:24:08.603  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.604  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b6df23e removed from the list
07-26 15:24:08.604  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.604  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@793389f removed from the list
07-26 15:24:08.604  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:24:08.604  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.605   871  4184 D DhcpClient: Receive thread started
07-26 15:24:08.605  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.605  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.606  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:24:08.606  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:24:08.606  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:24:08.606  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@793389f not in the list
07-26 15:24:08.606  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.606  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.607  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:24:08.607  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:24:08.607  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.607  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@552f44a removed from the list
,07-26 15:24:08.607  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:24:08.607  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.608  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:24:08.608  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.608  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ebf5b5 removed from the list
07-26 15:24:08.608  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:24:08.608  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd40b16 added. We now have 2 listener(s)
,07-26 15:24:08.610  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-26 15:24:08.610  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:24:08.610  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:24:08.611  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:08.611  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad9c97 added. We now have 9 listener(s)
,07-26 15:24:08.611  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:24:08.611  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:24:08.612  4127  4143 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-26 15:24:08.612  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:24:08.614  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:08.618  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:08.619  4127  4143 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-26 15:24:08.619  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:24:08.620  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:24:08.620  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:24:08.621  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:24:08.621  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd2266d added. We now have 3 listener(s),
07-26 15:24:08.622  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:08.622  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-26 15:24:08.623  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:24:08.623  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:24:08.623  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:24:08.623  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97dc2a2 added. We now have 10 listener(s)
07-26 15:24:08.623  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:24:08.623  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:24:08.624  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:08.624  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:24:08.624  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-26 15:24:08.624  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:24:08.624  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:24:08.627  4127  4143 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-26 15:24:08.627  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
07-26 15:24:08.627  4127  4146 D BtGatt.ScanManager: stopping BLe Batch
,07-26 15:24:08.628  3761  3809 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:24:08.628  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-26 15:24:08.631  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false,
07-26 15:24:08.632  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,07-26 15:24:08.632  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-26 15:24:08.633  4127  4143 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-26 15:24:08.633  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0,
07-26 15:24:08.634  4127  4146 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-26 15:24:08.635  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-26 15:24:08.636  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 15:24:08.636  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-26 15:24:08.636  3761  3809 D BluetoothAdapter: STATE_ON
,07-26 15:24:08.638  4127  4167 D BtGatt.GattService: registerClient() - UUID=adf06988-7b92-43df-8805-9074b6f221be
,07-26 15:24:08.639  4127  4143 D BtGatt.GattService: onClientRegistered() - UUID=adf06988-7b92-43df-8805-9074b6f221be, clientIf=5
,07-26 15:24:08.639  3761  3771 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-26 15:24:08.639  4127  4143 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-26 15:24:08.639  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.639  4127  4138 D BtGatt.GattService: start scan with filters
,07-26 15:24:08.642  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-26 15:24:08.642  4127  4146 D BtGatt.ScanManager: handling starting scan
07-26 15:24:08.642  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,07-26 15:24:08.642  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
07-26 15:24:08.642  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING],
,07-26 15:24:08.646  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-26 15:24:08.646  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-26 15:24:08.646  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-26 15:24:08.647  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,07-26 15:24:08.648  4127  4143 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
07-26 15:24:08.648  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.649  4127  4146 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-26 15:24:08.650  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,07-26 15:24:08.650  3761  3809 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
07-26 15:24:08.650  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-26 15:24:08.650  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:24:08.650  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:24:08.651  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:24:08.651  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:24:08.651  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 15:24:08.651  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-26 15:24:08.651  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@dd40b16 removed from the list
07-26 15:24:08.651  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:24:08.651  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad9c97 removed from the list
,07-26 15:24:08.651  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:24:08.651  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:24:08.652  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.652  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,07-26 15:24:08.652  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.652  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-26 15:24:08.653  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-26 15:24:08.653  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:24:08.653  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.653  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7ad9c97 not in the list
,07-26 15:24:08.653  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,07-26 15:24:08.654  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:24:08.654  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-26 15:24:08.654  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,07-26 15:24:08.654  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-26 15:24:08.655  3761  3809 D BluetoothAdapter: STATE_ON
,07-26 15:24:08.655  4127  4143 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
,07-26 15:24:08.655  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:24:08.655  4127  4146 D BtGatt.ScanManager: Starting BLE batch scan
,07-26 15:24:08.655  4127  4146 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-26 15:24:08.655  4127  4138 D BtGatt.GattService: stopScan() - queue size =1
07-26 15:24:08.656  4127  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 15:24:08.656  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:24:08.656  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-26 15:24:08.656  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,07-26 15:24:08.656  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
07-26 15:24:08.656  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-26 15:24:08.657  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:24:08.657  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
07-26 15:24:08.658  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:24:08.658  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:24:08.658  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.659  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:24:08.659  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:24:08.659  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.659  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:24:08.660  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,07-26 15:24:08.660  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:24:08.660  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@97dc2a2 removed from the list
07-26 15:24:08.660  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:24:08.660  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.660  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.661  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.661  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fd2266d removed from the list
07-26 15:24:08.661  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:24:08.661  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71966ee added. We now have 2 listener(s)
,07-26 15:24:08.663  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-26 15:24:08.664  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:24:08.664  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:24:08.664  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:08.664  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d41878f added. We now have 9 listener(s)
07-26 15:24:08.664  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:24:08.665  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-26 15:24:08.666  4127  4143 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,07-26 15:24:08.666  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.668  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:08.670  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:08.672  4127  4143 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-26 15:24:08.672  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.673  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-26 15:24:08.673  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:24:08.674  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:24:08.674  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c6b625 added. We now have 3 listener(s)
,07-26 15:24:08.675  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:24:08.676  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-26 15:24:08.676  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-26 15:24:08.676  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:24:08.676  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:24:08.676  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-26 15:24:08.676  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b903fa added. We now have 10 listener(s)
07-26 15:24:08.676  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:24:08.676  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-26 15:24:08.677  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-26 15:24:08.677  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-26 15:24:08.677  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-26 15:24:08.679  4127  4143 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-26 15:24:08.679  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.679  4127  4146 D BtGatt.ScanManager: stopping BLe Batch
,07-26 15:24:08.680  3761  3809 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
07-26 15:24:08.680  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-26 15:24:08.684  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-26 15:24:08.684  4127  4143 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
07-26 15:24:08.684  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.684  4127  4146 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,07-26 15:24:08.685  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
07-26 15:24:08.685  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-26 15:24:08.687   871  1307 E native  : do suspend false
,07-26 15:24:08.688  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,07-26 15:24:08.688  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
07-26 15:24:08.688  3761  3809 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=76, mManufacturerData=null, mManufacturerDataMask=null]
,07-26 15:24:08.689  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:24:08.689  4127  4143 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-26 15:24:08.689  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:24:08.692  4127  4138 D BtGatt.GattService: registerClient() - UUID=0bf765a2-522d-4ea1-97f9-a9aa70ba8a34
,07-26 15:24:08.692  4127  4143 D BtGatt.GattService: onClientRegistered() - UUID=0bf765a2-522d-4ea1-97f9-a9aa70ba8a34, clientIf=5
07-26 15:24:08.692  3761  3802 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,07-26 15:24:08.692  4127  4164 D BtGatt.GattService: start scan with filters
,07-26 15:24:08.695  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,07-26 15:24:08.695  4127  4146 D BtGatt.ScanManager: handling starting scan
07-26 15:24:08.695  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
07-26 15:24:08.695  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
,07-26 15:24:08.695  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,07-26 15:24:08.697   871  1949 D DhcpClient: Broadcasting DHCPDISCOVER
,07-26 15:24:08.698  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-26 15:24:08.699  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,07-26 15:24:08.699  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,07-26 15:24:08.700  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK,
07-26 15:24:08.701  4127  4143 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,07-26 15:24:08.701  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.701  4127  4146 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,07-26 15:24:08.704  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:24:08.704  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-26 15:24:08.704  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-26 15:24:08.704  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:24:08.705  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:24:08.705  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
07-26 15:24:08.705  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.705  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@71966ee removed from the list
07-26 15:24:08.705  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:24:08.705  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d41878f removed from the list
07-26 15:24:08.705  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
,07-26 15:24:08.705  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:24:08.705  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:24:08.705  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
07-26 15:24:08.705  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.706  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:24:08.706  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:24:08.706  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:24:08.707  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-26 15:24:08.707  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d41878f not in the list
07-26 15:24:08.707  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-26 15:24:08.707  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-26 15:24:08.707  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,07-26 15:24:08.707  4127  4143 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=15
07-26 15:24:08.707  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-26 15:24:08.707  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
07-26 15:24:08.707  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:24:08.708  4127  4146 D BtGatt.ScanManager: Starting BLE batch scan
07-26 15:24:08.708  3761  3809 D BluetoothAdapter: STATE_ON
07-26 15:24:08.708  4127  4146 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
07-26 15:24:08.708  4127  4138 D BtGatt.GattService: stopScan() - queue size =1
07-26 15:24:08.708  4127  4164 D BtGatt.GattService: unregisterClient() - clientIf=5
,07-26 15:24:08.709  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-26 15:24:08.709  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
07-26 15:24:08.709  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
07-26 15:24:08.709  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED],
07-26 15:24:08.709  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
07-26 15:24:08.709   871  4184 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 OFFER, ip /192.168.1.117, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172783, domain null
07-26 15:24:08.710   871  1949 D DhcpClient: Got pending lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172783 seconds,
07-26 15:24:08.710  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:24:08.710  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,07-26 15:24:08.710  3761  3809 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-26 15:24:08.710  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-26 15:24:08.710   871  1949 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.117 serverid=192.168.1.1
07-26 15:24:08.711  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-26 15:24:08.711  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:24:08.711  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-26 15:24:08.712  3761  3761 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-26 15:24:08.712  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:24:08.712  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:24:08.712  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.712  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6b903fa removed from the list
07-26 15:24:08.712  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-26 15:24:08.712  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.712  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.712  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.712  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5c6b625 removed from the list
07-26 15:24:08.713  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-26 15:24:08.713  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58365c6 added. We now have 2 listener(s)
07-26 15:24:08.715  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-26 15:24:08.715  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-26 15:24:08.715  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-26 15:24:08.715  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:08.715  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f18d987 added. We now have 9 listener(s)
07-26 15:24:08.715  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-26 15:24:08.715  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-26 15:24:08.718  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-26 15:24:08.718  4127  4143 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
07-26 15:24:08.718  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-26 15:24:08.721  3761  3809 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-26 15:24:08.722   871  4184 D DhcpClient: Received packet: f8:cf:c5:d9:e5:62 ACK: your new IP /192.168.1.117, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,07-26 15:24:08.722   871  1949 D DhcpClient: Confirmed lease: IP address 192.168.1.117/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,07-26 15:24:08.724  4127  4143 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,07-26 15:24:08.724  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,07-26 15:24:08.724   372   869 D CommandListener: Setting iface cfg
,07-26 15:24:08.725  3761  3809 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-26 15:24:08.725  3761  3809 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-26 15:24:08.725  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-26 15:24:08.725  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5684dd added. We now have 3 listener(s)
,07-26 15:24:08.727  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:08.727   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
07-26 15:24:08.728  3761  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-26 15:24:08.729  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
07-26 15:24:08.729  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-26 15:24:08.729  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-26 15:24:08.729  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-26 15:24:08.729  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a401852 added. We now have 10 listener(s)
,07-26 15:24:08.729  3761  3809 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-26 15:24:08.729  3761  3809 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-26 15:24:08.729  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-26 15:24:08.729   871  1949 D DhcpClient: Scheduling renewal in 86399s
,07-26 15:24:08.730  3761  3809 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-26 15:24:08.730  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:24:08.730  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.730  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-26 15:24:08.730  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.730  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@58365c6 removed from the list
07-26 15:24:08.730  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.730  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f18d987 removed from the list
07-26 15:24:08.730  3761  3809 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:24:08.730  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.730   871  1307 E native  : do suspend true
07-26 15:24:08.730  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.731  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.732  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:24:08.732  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-26 15:24:08.732  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.732  3761  3809 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f18d987 not in the list
07-26 15:24:08.732  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.732  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.733  4127  4143 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=16
07-26 15:24:08.733  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.733  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-26 15:24:08.733  4127  4146 D BtGatt.ScanManager: stopping BLe Batch
,07-26 15:24:08.733  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-26 15:24:08.733  3761  3809 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.733  3761  3809 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a401852 removed from the list
07-26 15:24:08.734  3761  3809 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:24:08.734  3761  3809 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-26 15:24:08.734  3761  3809 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.734  3761  3809 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.734  3761  3809 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d5684dd removed from the list
07-26 15:24:08.734  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 15:24:08.735  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,07-26 15:24:08.735  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-26 15:24:08.735  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-26 15:24:08.735  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-26 15:24:08.735  3761  3809 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
07-26 15:24:08.739  4127  4143 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,07-26 15:24:08.739  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.739  4127  4146 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
07-26 15:24:08.741  3761  4185 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 451, name: My test thread name)
07-26 15:24:08.741  3761  4185 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 451, thread name: My test thread name)
07-26 15:24:08.741  3761  4185 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 451, name: My test thread name)
,07-26 15:24:08.744   871  1307 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
07-26 15:24:08.745   871  1307 D WifiConfigStore: No blacklist allowed without epno enabled
07-26 15:24:08.746   871  1309 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
07-26 15:24:08.746  4127  4143 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,07-26 15:24:08.746  4127  4143 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
07-26 15:24:08.747   871  1309 D ConnectivityService: Adding iface wlan0 to network 102
07-26 15:24:08.749   871  1307 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
07-26 15:24:08.749  3761  4186 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 453, name: My test thread name)
,07-26 15:24:08.750  3761  4186 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 453, thread name: My test thread name)
07-26 15:24:08.750  3761  4186 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 453, name: My test thread name)
07-26 15:24:08.752  3761  3809 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-26 15:24:08.752  3761  3809 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
,07-26 15:24:08.752  3761  3809 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
,07-26 15:24:08.752  3761  3809 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
07-26 15:24:08.752  3761  3809 D com.test.thalitest.ThaliTestRunner: Total duration: 22943 ms
,07-26 15:24:08.753  3761  3809 I jxcore-log: Total number of executed tests:  84
07-26 15:24:08.753  3761  3809 I jxcore-log: 
07-26 15:24:08.753  3761  3809 I jxcore-log: Number of passed tests:  84
07-26 15:24:08.753  3761  3809 I jxcore-log: 
,07-26 15:24:08.754  3761  3809 I jxcore-log: Number of failed tests:  0
07-26 15:24:08.754  3761  3809 I jxcore-log: 
07-26 15:24:08.754  3761  3809 I jxcore-log: Number of ignored tests:  0
07-26 15:24:08.754  3761  3809 I jxcore-log: 
07-26 15:24:08.754  3761  3809 I jxcore-log: Total duration:  22943
07-26 15:24:08.754  3761  3809 I jxcore-log: 
07-26 15:24:08.758  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.758  3761  3809 I jxcore-log: 
,07-26 15:24:08.759  3761  3761 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Unsupported return type."", source: file:///android_asset/www/js/thali_main.js (57)
07-26 15:24:08.759  3761  3761 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
07-26 15:24:08.761  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.761  3761  3809 I jxcore-log: 
,07-26 15:24:08.762  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.762  3761  3809 I jxcore-log: 
07-26 15:24:08.763  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-26 15:24:08.763  3761  3809 I jxcore-log: 
07-26 15:24:08.763   871  2848 I ActivityManager: Killing 3627:com.google.android.apps.docs/u0a46 (adj 15): empty #17
07-26 15:24:08.773  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:24:08.773  3761  3809 I jxcore-log: 
07-26 15:24:08.774  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.774  3761  3809 I jxcore-log: 
07-26 15:24:08.775  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-26 15:24:08.775  3761  3809 I jxcore-log: 
07-26 15:24:08.776  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:24:08.776  3761  3809 I jxcore-log: 
07-26 15:24:08.777  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.777  3761  3809 I jxcore-log: 
07-26 15:24:08.777  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-26 15:24:08.777  3761  3809 I jxcore-log: 
07-26 15:24:08.778  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:24:08.778  3761  3809 I jxcore-log: 
07-26 15:24:08.779   871  1309 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-26 15:24:08.779   871  1309 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
07-26 15:24:08.780   871  1309 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
07-26 15:24:08.781   871  1309 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
07-26 15:24:08.782   871  1309 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,07-26 15:24:08.784  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-26 15:24:08.784  3761  3809 I jxcore-log: 
07-26 15:24:08.785  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:24:08.785  3761  3809 I jxcore-log: 
,07-26 15:24:08.787  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.787  3761  3809 I jxcore-log: 
,07-26 15:24:08.788  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.788  3761  3809 I jxcore-log: 
07-26 15:24:08.788  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.788  3761  3809 I jxcore-log: 
07-26 15:24:08.789  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.789  3761  3809 I jxcore-log: 
07-26 15:24:08.789  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.789  3761  3809 I jxcore-log: 
07-26 15:24:08.790  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.790  3761  3809 I jxcore-log: 
,07-26 15:24:08.791  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.791  3761  3809 I jxcore-log: 
07-26 15:24:08.792  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.792  3761  3809 I jxcore-log: 
07-26 15:24:08.792  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.792  3761  3809 I jxcore-log: 
07-26 15:24:08.793  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-26 15:24:08.793  3761  3809 I jxcore-log: 
,07-26 15:24:08.794  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.794  3761  3809 I jxcore-log: 
07-26 15:24:08.795  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.795  3761  3809 I jxcore-log: 
07-26 15:24:08.795  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.795  3761  3809 I jxcore-log: 
,07-26 15:24:08.798  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.798  3761  3809 I jxcore-log: 
,07-26 15:24:08.799  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.799  3761  3809 I jxcore-log: 
,07-26 15:24:08.800  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.800  3761  3809 I jxcore-log: 
,07-26 15:24:08.801  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.801  3761  3809 I jxcore-log: 
,07-26 15:24:08.802  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.802  3761  3809 I jxcore-log: 
,07-26 15:24:08.803  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.803  3761  3809 I jxcore-log: 
07-26 15:24:08.804  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-26 15:24:08.804  3761  3809 I jxcore-log: 
07-26 15:24:08.804  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.804  3761  3809 I jxcore-log: 
07-26 15:24:08.805  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.805  3761  3809 I jxcore-log: 
07-26 15:24:08.805  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.805  3761  3809 I jxcore-log: 
07-26 15:24:08.806  3761  3801 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 46ms. Plugin should use CordovaInterface.getThreadPool().
07-26 15:24:08.807   871   884 W ActivityManager: Failed to clear dns cache for: com.google.android.apps.docs
,07-26 15:24:08.809  3761  3761 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-26 15:24:08.809  3761  3761 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
07-26 15:24:08.809  3761  3761 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-26 15:24:08.809  3761  3761 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-26 15:24:08.809  3761  3761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-26 15:24:08.809  3761  3761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-26 15:24:08.809  3761  3761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@689ed39 removed from the list
,07-26 15:24:08.809  3761  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-26 15:24:08.809  3761  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@593bd2c removed from the list
07-26 15:24:08.809  3761  3761 D io.jxcore.node.ConnectivityMonitor: stop
07-26 15:24:08.809  3761  3761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,07-26 15:24:08.810  3761  3761 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-26 15:24:08.812   871  1309 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,07-26 15:24:08.821   871  1309 D ConnectivityService: scheduleUnvalidatedPrompt 102
,07-26 15:24:08.821   871  1309 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,07-26 15:24:08.821   871  1307 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
07-26 15:24:08.821   871  1309 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
07-26 15:24:08.821   871  1309 D ConnectivityService:    accepting network in place of null
07-26 15:24:08.822   871  1307 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,07-26 15:24:08.823   871  1309 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::facf:c5ff:fed9:e562/64,192.168.1.117/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,07-26 15:24:08.833  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.833  3761  3809 I jxcore-log: 
,07-26 15:24:08.835  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-26 15:24:08.835  3761  3809 I jxcore-log: 
,07-26 15:24:08.856  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:24:08.856  3761  3809 I jxcore-log: 
,07-26 15:24:08.856  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.856  3761  3809 I jxcore-log: 
07-26 15:24:08.857  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-26 15:24:08.857  3761  3809 I jxcore-log: 
07-26 15:24:08.858  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:24:08.858  3761  3809 I jxcore-log: 
07-26 15:24:08.858  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.858  3761  3809 I jxcore-log: 
,07-26 15:24:08.859  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}
07-26 15:24:08.859  3761  3809 I jxcore-log: 
07-26 15:24:08.859  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-26 15:24:08.859  3761  3809 I jxcore-log: 
07-26 15:24:08.860  3761  3809 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-26 15:24:08.860  3761  3809 I jxcore-log: 
07-26 15:24:08.860   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:24:08.896   372   869 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,07-26 15:24:08.899   871  1309 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,07-26 15:24:08.899   871  1309 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
07-26 15:24:08.902   871   888 D Tethering: MasterInitialState.processMessage what=3
07-26 15:24:08.905   871  1309 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,07-26 15:24:08.932  2061  2061 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,07-26 15:24:08.935  2061  2061 D SystemUpdateService: onCreate
,07-26 15:24:08.937  2061  2061 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,07-26 15:24:08.961  2061  2061 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-26 15:24:08.964  2061  2349 I iu.UploadsManager: num queued entries: 0
,07-26 15:24:08.964  2061  2349 I iu.UploadsManager: num updated entries: 0
,07-26 15:24:08.973  2061  4198 I SystemUpdateService: active receiver: enabled
,07-26 15:24:08.975  2061  2061 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,07-26 15:24:08.976  2061  2061 I Kids    : [GCoreUtils] Current gmscore version, 8186438 is smaller than the required version 8400000
,07-26 15:24:08.978  3928  3928 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,07-26 15:24:08.982  3928  3928 D SprintDMHelper: simOperator: 
,07-26 15:24:08.983  3928  3928 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,07-26 15:24:08.988  2061  4200 I MDM     : [237] SitrepService.onHandleIntent: sending sitrep: [0, 2, [CVPkGyZEl5KR3PJQxSWLrDkaNmU], null]
,07-26 15:24:08.991  2061  4200 W BaseAppContext: Using Auth Proxy for data requests.
,07-26 15:24:09.037  2061  4200 V GoogleAuthProtoRequest: [237] a.<init>: mAccountName set to: thalitester@gmail.com
,07-26 15:24:09.051  2061  2349 I iu.SyncManager: NEXT; no task
,07-26 15:24:09.070  2061  4198 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,07-26 15:24:09.096  2061  4198 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,07-26 15:24:09.096  2061  4198 I SystemUpdateService: now status is 0 (complete)
07-26 15:24:09.096  2061  4198 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
07-26 15:24:09.096  2061  4198 I SystemUpdateService: file has been verified
07-26 15:24:09.096  2061  4198 I SystemUpdateService: OTA package size = 12249756
,07-26 15:24:09.114  2061  4198 I SystemUpdateService: showing system update notification
,07-26 15:24:09.120  1537  1945 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/android_device_manager
,07-26 15:24:09.120  1537  1945 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/android_device_manager without consulting the cloud.
07-26 15:24:09.120  1537  1945 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-26 15:24:09.120  1537  1945 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-26 15:24:09.136  2061  2061 D SystemUpdateService: onDestroy
,07-26 15:24:09.143  2061  4200 E MDM     : [237] SitrepService.a: Error sending sitrep.
,07-26 15:24:09.689  4192  4192 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,07-26 15:24:09.696  4192  4192 D AndroidRuntime: CheckJNI is OFF
,07-26 15:24:09.744  4192  4192 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,07-26 15:24:09.791  4192  4192 I Radio-JNI: register_android_hardware_Radio DONE
,07-26 15:24:09.813  4192  4192 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-26 15:24:09.821   871   884 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,07-26 15:24:09.822   871   884 I ActivityManager: Killing 3761:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,07-26 15:24:09.935   871  2303 D GraphicsStats: Buffer count: 2
07-26 15:24:09.936   871  1308 D WifiService: Client connection lost with reason: 4
,07-26 15:24:09.944   871  2843 W ActivityManager: Spurious death for ProcessRecord{411178 0:com.test.thalitest/u0a0}, curProc for 3761: null
,07-26 15:24:09.955   871   894 W PackageSettings: Skipping PackageSetting{d95c051 com.example.hello/10273} due to missing metadata
,07-26 15:24:09.996   871   894 I art     : Starting a blocking GC Explicit
,07-26 15:24:10.047   871   894 I art     : Explicit concurrent mark sweep GC freed 23365(1484KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/43MB, paused 648us total 50.882ms
,07-26 15:24:10.081   871   894 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,07-26 15:24:10.089  4192  4192 I art     : System.exit called, status: 0
,07-26 15:24:10.089  4192  4192 I AndroidRuntime: VM exiting with result code 0.
,07-26 15:24:10.098   871   894 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,07-26 15:24:10.145  4127  4127 D BluetoothMapAppObserver: onReceive
,07-26 15:24:10.145  4127  4127 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
07-26 15:24:10.147  2019  2089 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
07-26 15:24:10.157   871  1299 I InputReader: Reconfiguring input devices.  changes=0x00000010
07-26 15:24:10.157  3567  3567 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,07-26 15:24:10.182  1645  1645 I Keyboard.Facilitator: resetDictionaries() : en_US
,07-26 15:24:10.192   871  2848 I ActivityManager: Start proc 4218:android.process.acore/u0a5 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,07-26 15:24:10.205  1645  4228 I Keyboard.Facilitator.DecoderInitializer: run()
,07-26 15:24:10.212  1737  1737 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,07-26 15:24:10.215  1645  4228 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
07-26 15:24:10.215  1645  4228 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/UserHistory.en_US.dict.tmp
07-26 15:24:10.215  1645  4228 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
07-26 15:24:10.216  1645  4228 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Personal.en_US.dict.tmp
07-26 15:24:10.216  1645  4228 E native  : dynamic-lm.cc:266 Cannot open fd for /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
07-26 15:24:10.216  1645  4228 E native  : dynamic-lm.cc:257 Cannot write DynamicLm to /data/user/0/com.google.android.inputmethod.latin/files/Contacts.dict.tmp
07-26 15:24:10.216  1645  4228 I Decoder : createOrResetDecoder
,07-26 15:24:10.219   871  1305 W AtomicFile: Couldn't rename file /data/system/netpolicy.xml to backup file /data/system/netpolicy.xml.bak
,07-26 15:24:10.253   871   871 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-26 15:24:10.258   871  2152 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3761 uid 10000
,07-26 15:24:10.259  1645  1645 I Keyboard.Facilitator: onFinishInput()
,07-26 15:24:10.275  4218  4218 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm
,07-26 15:24:10.279   871   883 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,07-26 15:24:10.279   871   883 E PackageManager: Failed to write settings, restoring backup
07-26 15:24:10.279   871   883 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
07-26 15:24:10.279   871   883 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
07-26 15:24:10.279   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
07-26 15:24:10.279   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
07-26 15:24:10.279   871   883 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
07-26 15:24:10.279   871   883 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:24:10.279   871   883 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:24:10.279   871   883 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:24:10.283   871   884 E DropBoxManagerService: Can't write: system_server_wtf
07-26 15:24:10.283   871   884 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
07-26 15:24:10.283   871   884 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:24:10.283   871   884 E DropBoxManagerService: 	... 13 more
,07-26 15:24:10.296  1748  1822 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,07-26 15:24:10.310   871  1381 I ActivityManager: Start proc 4231:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
07-26 15:24:10.311  1748  1822 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
07-26 15:24:10.311  1748  1822 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1748
07-26 15:24:10.311  1748  1822 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:24:10.311  1748  1822 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-26 15:24:10.313   871   881 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
07-26 15:24:10.317   871  4241 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:24:10.317   871  4241 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop121.tmp: open failed: EROFS (Read-only file system)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:24:10.317   871  4241 E DropBoxManagerService: 	... 5 more
,07-26 15:24:10.329  1748  1822 I Process : Sending signal. PID: 1748 SIG: 9
,07-26 15:24:10.357  1537  1537 I ConfigService: onCreate
,07-26 15:24:10.376  1537  4247 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-26 15:24:10.376  1537  4247 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,07-26 15:24:10.393  4218  4218 W System  : ClassLoader referenced unknown path: /system/app/UserDictionaryProvider/lib/arm
,07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
07-26 15:24:10.394  1537  4247 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,07-26 15:24:10.397  1537  4247 W SQLiteOpenHelper: Opened config.db in read-only mode
,07-26 15:24:10.410  1645  4228 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,07-26 15:24:10.414   871  1381 D GraphicsStats: Buffer count: 1
07-26 15:24:10.414   871  1381 I WindowState: WIN DEATH: Window{70eb67 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,07-26 15:24:10.423   871  4183 D NetlinkSocketObserver: NeighborEvent{elapsedMs=347316, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-26 15:24:10.430   871   881 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1748) has died
,07-26 15:24:10.431   871   881 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,07-26 15:24:10.432   871   881 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
07-26 15:24:10.450   871   884 I ActivityManager: Start proc 4251:com.google.android.googlequicksearchbox/u0a28 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-26 15:24:10.470   871  1412 I ActivityManager: Start proc 4264:com.android.musicfx/u0a18 for broadcast com.android.musicfx/.Compatibility$Receiver
,07-26 15:24:10.503  4218  4262 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,07-26 15:24:10.509  1645  4228 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,07-26 15:24:10.510  1645  4228 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
07-26 15:24:10.510  1645  4228 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,07-26 15:24:10.511  4251  4251 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:24:10.511  4251  4251 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,07-26 15:24:10.512  4251  4251 D AndroidRuntime: Shutting down VM
,07-26 15:24:10.520  1645  4228 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
07-26 15:24:10.520  1645  4228 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,07-26 15:24:10.524  4264  4264 W System  : ClassLoader referenced unknown path: /system/priv-app/MusicFX/lib/arm
,07-26 15:24:10.526  1645  4228 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
,07-26 15:24:10.526  1645  4228 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
07-26 15:24:10.526  1645  4228 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
07-26 15:24:10.526  1645  4228 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
07-26 15:24:10.526  1645  4228 I Keyboard.Facilitator.Delight2FileSweeper: run()
07-26 15:24:10.527  1645  4228 I Keyboard.Facilitator.RecurringTaskScheduler: run()
,07-26 15:24:10.527  1645  4228 I StatsUtilsManager: startPeriodStatsRecorder() : Success
07-26 15:24:10.527  1645  4228 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,07-26 15:24:10.534  4251  4251 E AndroidRuntime: FATAL EXCEPTION: main
07-26 15:24:10.534  4251  4251 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 4251
07-26 15:24:10.534  4251  4251 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
07-26 15:24:10.534  4251  4251 E AndroidRuntime: 	... 10 more
,07-26 15:24:10.535   871   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,07-26 15:24:10.536  4251  4251 I Process : Sending signal. PID: 4251 SIG: 9
07-26 15:24:10.537   871  4278 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:24:10.537   871  4278 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop122.tmp: open failed: EROFS (Read-only file system)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:24:10.537   871  4278 E DropBoxManagerService: 	... 5 more
,07-26 15:24:10.549  2061  4277 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,07-26 15:24:10.549  2061  4277 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,07-26 15:24:10.555  2061  4277 D GFEEDBACK_SendErrorReportOperation: Error doing instant send: java.io.IOException: failed to create reports directory
,07-26 15:24:10.555  2061  4277 E GFEEDBACK_SendErrorReportOperation: Error saving report: java.io.IOException: failed to create reports directory
,07-26 15:24:10.561  4218  4262 E SQLiteDatabase: Failed to open database '/data/user/0/com.android.providers.contacts/databases/contacts2.db'.
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:24:10.561  4218  4262 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:24:10.562  4218  4262 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
07-26 15:24:10.562  4218  4262 E AndroidRuntime: Process: android.process.acore, PID: 4218
07-26 15:24:10.562  4218  4262 E AndroidRuntime: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:191)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
07-26 15:24:10.562  4218  4262 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-26 15:24:10.564   871  4279 E DropBoxManagerService: Can't write: system_app_crash
07-26 15:24:10.564   871  4279 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop123.tmp: open failed: EROFS (Read-only file system)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
07-26 15:24:10.564   871  4279 E DropBoxManagerService: 	... 5 more
,07-26 15:24:10.572  4218  4262 I Process : Sending signal. PID: 4218 SIG: 9
,07-26 15:24:10.579  1537  1537 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
,07-26 15:24:10.580   280   337 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
