#### Test 833712394bbb446_thali01_motorola-Nexus 6 Logs


```
--------- beginning of main
08-31 03:04:41.847   872  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=311305, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-31 03:04:42.549  3841  3841 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-31 03:04:42.553  3841  3841 D AndroidRuntime: CheckJNI is OFF
08-31 03:04:42.588  3841  3841 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-31 03:04:42.631  3841  3841 I Radio-JNI: register_android_hardware_Radio DONE
08-31 03:04:42.650  3841  3841 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-31 03:04:42.654   872  2257 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-31 03:04:42.725   872  2257 I ActivityManager: Start proc 3850:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-31 03:04:42.735  3841  3841 D AndroidRuntime: Shutting down VM
08-31 03:04:42.798  3850  3850 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-31 03:04:42.822  3850  3850 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-31 03:04:42.832  3850  3850 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2286-2291)
08-31 03:04:42.832  3850  3850 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 03:04:42.848  3850  3850 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {74f565e}
08-31 03:04:42.848  3850  3850 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-31 03:04:42.848  3850  3850 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-31 03:04:42.853  3850  3850 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-31 03:04:42.855  3850  3850 E SysUtils: ApplicationContext is null in ApplicationStatus
08-31 03:04:42.870  3850  3850 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-31 03:04:42.879  3850  3850 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 03:04:42.879  3850  3850 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-31 03:04:42.879  3850  3850 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-31 03:04:42.879  3850  3850 I Adreno  : Build Date                       : 10/20/15
08-31 03:04:42.879  3850  3850 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-31 03:04:42.879  3850  3850 I Adreno  : Local Branch                     : M14
08-31 03:04:42.879  3850  3850 I Adreno  : Remote Branch                    : 
08-31 03:04:42.879  3850  3850 I Adreno  : Remote Branch                    : 
08-31 03:04:42.879  3850  3850 I Adreno  : Reconstruct Branch               : 
08-31 03:04:42.953   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@554af5a:true
,08-31 03:04:42.994  3850  3850 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-31 03:04:43.009  3850  3850 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-31 03:04:43.119  3850  3888 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-31 03:04:43.158  3850  3874 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-31 03:04:43.203  3850  3888 I OpenGLRenderer: Initialized EGL, version 1.4
,08-31 03:04:43.299   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +536ms (total +614ms)
,08-31 03:04:43.304  1881  1881 I Keyboard.Facilitator: onFinishInput()
,08-31 03:04:43.409  3850  3850 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3850
,08-31 03:04:43.563  3850  3850 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-31 03:04:43.731  3850  3891 D jxcore_app_log: JniHelper::setJavaVM(0xb4cfc000), pthread_self() = -1687746256
,08-31 03:04:43.749  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-31 03:04:43.749  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-31 03:04:43.749  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-31 03:04:43.749  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-31 03:04:43.749  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-31 03:04:43.749  3850  3891 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4826cd added. We now have 1 listener(s)
,08-31 03:04:43.766  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-31 03:04:43.770  3850  3891 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-31 03:04:43.772  3850  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-31 03:04:43.773  3850  3891 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-31 03:04:43.783  3850  3891 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89f22d0 added. We now have 1 listener(s)
08-31 03:04:43.783  3850  3891 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-31 03:04:43.788   872  1314 D WifiService: New client listening to asynchronous messages
,08-31 03:04:43.790  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-31 03:04:43.790  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-31 03:04:43.790  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-31 03:04:43.790  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-31 03:04:43.790  3850  3891 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-31 03:04:43.795  3850  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-31 03:04:43.796  3850  3891 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-31 03:04:43.804  3850  3891 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:04:43.805  3850  3891 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 03:04:43.805  3850  3891 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-31 03:04:43.805  3850  3891 D io.jxcore.node.ConnectivityMonitor: start: OK
08-31 03:04:43.806  3850  3891 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-31 03:04:43.807  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-31 03:04:43.809  3850  3850 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-31 03:04:43.835  3850  3850 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-31 03:04:44.712  3850  3896 W jxcore-log: Initializing JXcore engine
,08-31 03:04:44.713  3850  3896 W jxcore-log: JXcore engine is ready
,08-31 03:04:44.753  3896  3896 W Thread-321: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-31 03:04:44.753  3896  3896 W Thread-321: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11997]" dev="sockfs" ino=11997 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-31 03:04:44.753  3896  3896 W Thread-321: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-31 03:04:44.753  3896  3896 W Thread-321: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[29538]" dev="sockfs" ino=29538 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-31 03:04:44.769  3850  3896 W jxcore-log: Starting JXcore engine
,08-31 03:04:44.853  3850  3896 W jxcore-log: Platform android
08-31 03:04:44.853  3850  3896 W jxcore-log: 
,08-31 03:04:44.853  3850  3896 W jxcore-log: Process ARCH arm
08-31 03:04:44.853  3850  3896 W jxcore-log: 
,08-31 03:04:45.052  3850  3896 I jxcore-log: JXcore Cordova bridge is ready!
08-31 03:04:45.052  3850  3896 I jxcore-log: 
,08-31 03:04:45.052  3850  3896 W jxcore-log: JXcore engine is started
,08-31 03:04:45.059  3850  3891 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-31 03:04:45.064  3850  3850 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-31 03:04:49.082  3741  3897 I BooksSync: Starting books sync for 61035162, extras: ade
,08-31 03:04:49.109  3741  3898 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,08-31 03:04:49.123  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 03:04:49.125  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 03:04:49.152  1518  1529 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 03:04:49.153  1518  1529 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 03:04:49.153  1518  1529 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 03:04:49.153  1518  1529 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 03:04:49.175  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 03:04:49.177  1518  1518 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-31 03:04:49.196  1518  2343 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,08-31 03:04:49.196  1518  2343 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
08-31 03:04:49.196  1518  2343 I GLSUser : [GLSUser] Extracting token using key: Auth
08-31 03:04:49.196  1518  2343 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,08-31 03:04:49.212  3741  3898 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,08-31 03:04:49.214  3741  3897 E BooksSync: Soft error
08-31 03:04:49.214  3741  3897 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 03:04:49.214  3741  3897 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,08-31 03:04:49.214  3741  3897 E BooksSync: Sync error
08-31 03:04:49.214  3741  3897 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
08-31 03:04:49.214  3741  3897 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
08-31 03:04:49.214  3741  3897 I BooksSync: Finished books sync
,08-31 03:04:49.217   872   884 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 318457, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,08-31 03:04:53.752   872  1876 D NetlinkSocketObserver: NeighborEvent{elapsedMs=323210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-31 03:04:59.002  3850  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-31 03:04:59.002  3850  3896 I jxcore-log: 
,08-31 03:04:59.005  3850  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-31 03:04:59.005  3850  3896 I jxcore-log: 
,08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-31 03:04:59.019  3850  3896 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-31 03:04:59.026  3850  3896 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-31 03:04:59.028  3850  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-31 03:04:59.028  3850  3896 I jxcore-log: 
,08-31 03:04:59.030  3850  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-31 03:04:59.030  3850  3896 I jxcore-log: 
,08-31 03:04:59.388  3850  3896 I jxcore-log: Running unit tests
08-31 03:04:59.388  3850  3896 I jxcore-log: 
,08-31 03:04:59.389  3850  3896 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-31 03:04:59.389  3850  3896 I jxcore-log: Failed to execute UT.
08-31 03:04:59.389  3850  3896 I jxcore-log: 
08-31 03:04:59.391  3850  3896 I jxcore-log: Unit Test app is loaded
08-31 03:04:59.391  3850  3896 I jxcore-log: 
,08-31 03:04:59.396  3850  3896 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-31 03:04:59.396  3850  3896 I jxcore-log: 
,08-31 03:04:59.400  3850  3896 I jxcore-log: My device name is: motorola-Nexus 6
08-31 03:04:59.400  3850  3896 I jxcore-log: 
,08-31 03:04:59.402  3850  3896 I jxcore-log: WARN testUtils: myNameCallback not set!
08-31 03:04:59.402  3850  3896 I jxcore-log: 
,08-31 03:04:59.418  3850  3850 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-31 03:05:01.837  3850  3896 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-31 03:05:01.837  3850  3896 I jxcore-log: 
,08-31 03:05:02.291  3850  3896 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-31 03:05:02.291  3850  3896 I jxcore-log: 
,08-31 03:05:02.317  3850  3896 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-31 03:05:02.317  3850  3896 I jxcore-log: 
,08-31 03:05:03.703  3850  3896 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-31 03:05:03.703  3850  3896 I jxcore-log: 
,08-31 03:05:03.937  3850  3896 I jxcore-log: ERROR runTests: 
08-31 03:05:03.937  3850  3896 I jxcore-log: 
,08-31 03:05:03.940  3850  3896 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:05:03.940  3850  3896 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-31 03:05:03.941  3850  3896 I jxcore-log: WARN testUtils: logCallback not set!
08-31 03:05:03.941  3850  3896 I jxcore-log: 
,08-31 03:05:03.950  3850  3896 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _functionName: 'loadFile',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _lineNumber: '26',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _columnNumber: '11',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-31 03:05:03.950  3850  3896 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _functionName: '',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _lineNumber: '38',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _columnNumber: '7',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-31 03:05:03.950  3850  3896 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _functionName: '',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _lineNumber: '35',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _columnNumber: '3',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-31 03:05:03.950  3850  3896 I jxcore-log:   { _fileName: 'module.js',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _functionName: '$w.prototype._compile',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _lineNumber: '621',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _columnNumber: '8',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-31 03:05:03.950  3850  3896 I jxcore-log:   { _fileName: 'module.js',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _lineNumber: '651',
08-31 03:05:03.950  3850  3896 I jxcore-log:     _columnNumber: '1',
08-31 03:05:03.950  3850  3896 I jxcore-log:    
,08-31 03:05:03.950  3850  3896 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-31 03:05:03.950  3850  3896 I jxcore-log: 
,08-31 03:05:03.951  3850  3896 E jxcore-log: Error: 
08-31 03:05:03.951  3850  3896 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-31 03:05:03.951  3850  3896 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-31 03:05:03.951  3850  3896 E jxcore-log: 
,08-31 03:05:04.606  3899  3899 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-31 03:05:04.611  3899  3899 D AndroidRuntime: CheckJNI is OFF
,08-31 03:05:04.646  3899  3899 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-31 03:05:04.688  3899  3899 I Radio-JNI: register_android_hardware_Radio DONE
,08-31 03:05:04.709  3899  3899 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-31 03:05:04.725   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-31 03:05:04.726   872   885 I ActivityManager: Killing 3850:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-31 03:05:04.823   872   895 W PackageSettings: Skipping PackageSetting{f574265 com.example.hello/10273} due to missing metadata
,08-31 03:05:04.845   872  2258 D GraphicsStats: Buffer count: 2
,08-31 03:05:04.845   872  1693 I WindowState: WIN DEATH: Window{b67a30a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-31 03:05:04.845   872  1314 D WifiService: Client connection lost with reason: 4
,08-31 03:05:04.882   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-31 03:05:04.882   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-31 03:05:04.883   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-31 03:05:04.883   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-31 03:05:04.883   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:04.883   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:04.883   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:04.883   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-31 03:05:04.883   872   885 I ActivityManager:   Force finishing activity ActivityRecord{4c53a77 u0 com.test.thalitest/.MainActivity t2}
08-31 03:05:04.884   872   895 I art     : Starting a blocking GC Explicit
,08-31 03:05:04.893   872  1695 W ActivityManager: Spurious death for ProcessRecord{db87f5b 0:com.test.thalitest/u0a0}, curProc for 3850: null
,08-31 03:05:04.935   872   895 I art     : Explicit concurrent mark sweep GC freed 17799(1251KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 29MB/43MB, paused 827us total 50.066ms
,08-31 03:05:04.954   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-31 03:05:04.959  3899  3899 I art     : System.exit called, status: 0
08-31 03:05:04.959  3899  3899 I AndroidRuntime: VM exiting with result code 0.
,08-31 03:05:04.963   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-31 03:05:04.975   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
08-31 03:05:04.982   872  1305 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-31 03:05:04.988  2020  2280 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-31 03:05:04.988  2689  2689 D BluetoothMapAppObserver: onReceive
08-31 03:05:04.988  2689  2689 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-31 03:05:04.989  1881  1881 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-31 03:05:04.994  3624  3624 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-31 03:05:05.004  1881  3910 I Keyboard.Facilitator.DecoderInitializer: run()
,08-31 03:05:05.006  1881  3910 I Decoder : createOrResetDecoder
,08-31 03:05:05.029  1953  1953 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-31 03:05:05.075  1518  1518 I ConfigService: onCreate
,08-31 03:05:05.075   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-31 03:05:05.078  1696  3913 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-31 03:05:05.102  1518  1518 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-31 03:05:05.102  1518  1518 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-31 03:05:05.112  1881  3910 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-31 03:05:05.122  1696  3913 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-31 03:05:05.124  1696  3913 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-31 03:05:05.124  1696  3913 E AndroidRuntime: Process: android.process.acore, PID: 1696
08-31 03:05:05.124  1696  3913 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.124  1696  3913 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:05.124   872  1981 I ActivityManager: Start proc 3917:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,08-31 03:05:05.125  1964  2059 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-31 03:05:05.125  1964  2059 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1964
08-31 03:05:05.125  1964  2059 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.125  1964  2059 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:05.127   872  2035 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-31 03:05:05.128   872  3923 E DropBoxManagerService: Can't write: system_app_crash
08-31 03:05:05.128   872  3923 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 03:05:05.128   872  3923 E DropBoxManagerService: 	... 5 more
08-31 03:05:05.130  1964  2059 I Process : Sending signal. PID: 1964 SIG: 9
,08-31 03:05:05.154  1696  3913 I Process : Sending signal. PID: 1696 SIG: 9
,08-31 03:05:05.155   872  3930 E DropBoxManagerService: Can't write: system_app_crash
08-31 03:05:05.155   872  3930 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 03:05:05.155   872  3930 E DropBoxManagerService: 	... 5 more
,08-31 03:05:05.174  1744  3931 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-31 03:05:05.179  1744  3931 D AccountUtils: Clearing selected account for com.test.thalitest
,08-31 03:05:05.184  1881  3910 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-31 03:05:05.185  1881  3910 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-31 03:05:05.186  1881  3910 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-31 03:05:05.188  1881  3910 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-31 03:05:05.188  1881  3910 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-31 03:05:05.189  1881  3910 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-31 03:05:05.189  1881  3910 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-31 03:05:05.190  1881  3910 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-31 03:05:05.190  1881  3910 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-31 03:05:05.190  1881  3910 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-31 03:05:05.190  1881  3910 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-31 03:05:05.190  1881  3910 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-31 03:05:05.190  1881  3910 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-31 03:05:05.209   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
,08-31 03:05:05.235   872  1694 D GraphicsStats: Buffer count: 1
,08-31 03:05:05.235   872  1393 I WindowState: WIN DEATH: Window{6069b70 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-31 03:05:05.248   872  2258 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1964) has died
08-31 03:05:05.249   872  2258 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
08-31 03:05:05.250   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
,08-31 03:05:05.258  1744  3931 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-31 03:05:05.264  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 03:05:05.264  1744  1744 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 03:05:05.282   872  1695 I BroadcastQueue: Delay finish: com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver
,08-31 03:05:05.286  1744  3931 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.286  1744  3931 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.286  1744  3931 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:05.287  1744  3931 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-31 03:05:05.295  1744  3937 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 03:05:05.297  1744  1744 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-31 03:05:05.298  1744  1744 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-31 03:05:05.303  1744  3937 E DriveAsyncService: disk I/O error (code 3850)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-31 03:05:05.303  1744  3937 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,08-31 03:05:05.311  1744  3938 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	,at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.311  1744  3938 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 03:05:05.311  1744 , 3938 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.311  1744  3938 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-31 03:05:05.316   872  2257 I BroadcastQueue: Resuming delayed broadcast
08-31 03:05:05.316   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
08-31 03:05:05.318   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
08-31 03:05:05.333   872   883 I ActivityManager: Start proc 3944:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
08-31 03:05:05.333   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
08-31 03:05:05.339   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
08-31 03:05:05.341  2037  3941 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-31 03:05:05.345   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
,08-31 03:05:05.369  1744  3942 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 03:05:05.375   278   278 E lowmemorykiller: Error writing /proc/1696/oom_score_adj; errno=22
,08-31 03:05:05.395  1744  3938 W SQLiteOpenHelper: Opened metrics.db in read-only mode
,08-31 03:05:05.398  1744  3938 D GOOGLEHELP_CompatibleDatabase: Open SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db, release reference: 1
08-31 03:05:05.398  1744  3938 D GOOGLEHELP_CompatibleDatabase: Acquire reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 2
,08-31 03:05:05.405  1744  3938 E SQLiteLog: (8) statement aborts at 16: [DELETE FROM metrics WHERE app_package_name="com.test.thalitest"] attempt to write a readonly database
,08-31 03:05:05.405  1744  3938 D GOOGLEHELP_CompatibleDatabase: Release reference of SQLiteDatabase: /data/user/0/com.google.android.gms/databases/metrics.db: 1
,08-31 03:05:05.414  1744  3938 I Process : Sending signal. PID: 1744 SIG: 9
,08-31 03:05:05.428  2037  3941 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-31 03:05:05.435   872   882 I ActivityManager: Delaying start of: ServiceRecord{1e2c318 u0 com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService}
,08-31 03:05:05.437  2037  3941 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-31 03:05:05.438  2037  3941 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-31 03:05:05.438  2037  3941 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 2037
08-31 03:05:05.438  2037  3941 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.438  2037  3941 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-31 03:05:05.439   872  2251 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-31 03:05:05.440   872  2251 I ActivityManager: Killing 2037:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
,08-31 03:05:05.442   872  3960 E DropBoxManagerService: Can't write: system_app_crash
08-31 03:05:05.442   872  3960 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211),
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-31 03:05:05.442   872  3960 E DropBoxManagerService: 	... 5 more
,08-31 03:05:05.480  3944  3944 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-31 03:05:05.480  3944  3944 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-31 03:05:05.481  3944  3944 D AndroidRuntime: Shutting down VM

```
