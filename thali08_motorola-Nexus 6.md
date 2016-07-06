#### Test 72145431aac82a0_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
07-06 08:24:47.847  3479  3709 I BooksSync: Starting books sync for 61035162, extras: ade
,07-06 08:24:47.864  3479  3710 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
07-06 08:24:47.876  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-06 08:24:47.877  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-06 08:24:47.900  1500  2868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-06 08:24:47.900  1500  2868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-06 08:24:47.900  1500  2868 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:24:47.900  1500  2868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-06 08:24:47.924  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-06 08:24:47.925  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
07-06 08:24:47.943  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-06 08:24:47.943  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-06 08:24:47.943  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:24:47.943  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
07-06 08:24:47.961  3479  3710 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-06 08:24:47.962  3479  3709 E BooksSync: Soft error
07-06 08:24:47.962  3479  3709 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-06 08:24:47.962  3479  3709 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-06 08:24:47.962  3479  3709 E BooksSync: Sync error
07-06 08:24:47.962  3479  3709 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-06 08:24:47.962  3479  3709 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-06 08:24:47.962  3479  3709 I BooksSync: Finished books sync
07-06 08:24:47.969   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 257531, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
07-06 08:24:48.460  3711  3711 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
07-06 08:24:48.464  3711  3711 D AndroidRuntime: CheckJNI is OFF
07-06 08:24:48.499  3711  3711 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
07-06 08:24:48.542  3711  3711 I Radio-JNI: register_android_hardware_Radio DONE
07-06 08:24:48.563  3711  3711 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
07-06 08:24:48.568   876  1714 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-06 08:24:48.614   876  1714 I ActivityManager: Start proc 3721:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
07-06 08:24:48.627  3711  3711 D AndroidRuntime: Shutting down VM
07-06 08:24:48.698  3721  3721 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
07-06 08:24:48.721  3721  3721 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
07-06 08:24:48.732  3721  3721 I LibraryLoader: Time to load native libraries: 6 ms (timestamps 8690-8696)
07-06 08:24:48.732  3721  3721 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 08:24:48.745  3721  3721 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {9ed5ea}
07-06 08:24:48.746  3721  3721 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-06 08:24:48.747  3721  3721 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
07-06 08:24:48.752  3721  3721 I BrowserStartupController: Initializing chromium process, singleProcess=true
07-06 08:24:48.753  3721  3721 E SysUtils: ApplicationContext is null in ApplicationStatus
07-06 08:24:48.763  3721  3721 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
07-06 08:24:48.772  3721  3721 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-06 08:24:48.772  3721  3721 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
07-06 08:24:48.772  3721  3721 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
07-06 08:24:48.772  3721  3721 I Adreno  : Build Date                       : 10/20/15
07-06 08:24:48.772  3721  3721 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
07-06 08:24:48.772  3721  3721 I Adreno  : Local Branch                     : M14
07-06 08:24:48.772  3721  3721 I Adreno  : Remote Branch                    : 
07-06 08:24:48.772  3721  3721 I Adreno  : Remote Branch                    : 
07-06 08:24:48.772  3721  3721 I Adreno  : Reconstruct Branch               : 
07-06 08:24:48.853   876   893 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8377eef:true
,07-06 08:24:48.888  3721  3721 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-06 08:24:48.900  3721  3721 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,07-06 08:24:48.956  3721  3758 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,07-06 08:24:48.975  3721  3745 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,07-06 08:24:49.016  3721  3758 I OpenGLRenderer: Initialized EGL, version 1.4
,07-06 08:24:49.035  1661  1661 I Keyboard.Facilitator: onFinishInput()
,07-06 08:24:49.078   876   894 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +412ms (total +483ms)
,07-06 08:24:49.152  3721  3721 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3721
,07-06 08:24:49.353  3721  3721 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-06 08:24:49.505  3721  3761 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1687156432
,07-06 08:24:49.511  3721  3761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-06 08:24:49.511  3721  3761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-06 08:24:49.511  3721  3761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-06 08:24:49.511  3721  3761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-06 08:24:49.511  3721  3761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-06 08:24:49.512  3721  3761 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7aa4449 added. We now have 1 listener(s)
,07-06 08:24:49.514  3721  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,07-06 08:24:49.519  3721  3761 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,07-06 08:24:49.520  3721  3761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-06 08:24:49.520  3721  3761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-06 08:24:49.526  3721  3761 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4310b7c added. We now have 1 listener(s)
,07-06 08:24:49.526  3721  3761 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-06 08:24:49.529   876  1311 D WifiService: New client listening to asynchronous messages
,07-06 08:24:49.533  3721  3761 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,07-06 08:24:49.535  3721  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-06 08:24:49.535  3721  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
07-06 08:24:49.535  3721  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-06 08:24:49.535  3721  3761 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-06 08:24:49.542  3721  3761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-06 08:24:49.542  3721  3761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 08:24:49.552  3721  3761 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-06 08:24:49.552  3721  3761 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-06 08:24:49.552  3721  3761 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-06 08:24:49.554  3721  3761 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-06 08:24:49.558  3721  3721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-06 08:24:49.565  3721  3721 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-06 08:24:49.583  3721  3721 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-06 08:24:50.439  3721  3767 W jxcore-log: Initializing JXcore engine
,07-06 08:24:50.439  3721  3767 W jxcore-log: JXcore engine is ready
,07-06 08:24:50.473  3767  3767 W Thread-325: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8945 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,07-06 08:24:50.473  3767  3767 W Thread-325: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[10830]" dev="sockfs" ino=10830 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,07-06 08:24:50.473  3767  3767 W Thread-325: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,07-06 08:24:50.473  3767  3767 W Thread-325: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[22452]" dev="sockfs" ino=22452 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,07-06 08:24:50.489  3721  3767 W jxcore-log: Starting JXcore engine
,07-06 08:24:50.567  3721  3767 W jxcore-log: Platform android
07-06 08:24:50.567  3721  3767 W jxcore-log: 
,07-06 08:24:50.567  3721  3767 W jxcore-log: Process ARCH arm
07-06 08:24:50.567  3721  3767 W jxcore-log: 
,07-06 08:24:50.755  3721  3767 I jxcore-log: JXcore Cordova bridge is ready!
07-06 08:24:50.755  3721  3767 I jxcore-log: 
,07-06 08:24:50.756  3721  3767 W jxcore-log: JXcore engine is started
,07-06 08:24:50.770  3721  3761 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-06 08:24:50.776  3721  3721 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-06 08:25:00.518  3721  3767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-06 08:25:00.518  3721  3767 I jxcore-log: 
,07-06 08:25:00.521  3721  3767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-06 08:25:00.521  3721  3767 I jxcore-log: 
,07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-06 08:25:00.532  3721  3767 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-06 08:25:00.536  3721  3767 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-06 08:25:00.542  3721  3767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-06 08:25:00.542  3721  3767 I jxcore-log: 
,07-06 08:25:00.549  3721  3767 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-06 08:25:00.549  3721  3767 I jxcore-log: 
,07-06 08:25:00.894  3721  3767 I jxcore-log: Unit Test app is loaded
07-06 08:25:00.894  3721  3767 I jxcore-log: 
,07-06 08:25:00.900  3721  3767 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-06 08:25:00.900  3721  3767 I jxcore-log: 
,07-06 08:25:00.903  3721  3767 I jxcore-log: My device name is: motorola-Nexus 6
07-06 08:25:00.903  3721  3767 I jxcore-log: 
,07-06 08:25:00.905  3721  3767 I jxcore-log: WARN testUtils: myNameCallback not set!
07-06 08:25:00.905  3721  3767 I jxcore-log: 
,07-06 08:25:00.925  3721  3721 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-06 08:25:04.703  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
07-06 08:25:04.703  3721  3767 I jxcore-log: 
,07-06 08:25:05.082  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
07-06 08:25:05.082  3721  3767 I jxcore-log: 
,07-06 08:25:05.107  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
07-06 08:25:05.107  3721  3767 I jxcore-log: 
,07-06 08:25:05.112  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
07-06 08:25:05.112  3721  3767 I jxcore-log: 
,07-06 08:25:05.128  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
07-06 08:25:05.128  3721  3767 I jxcore-log: 
,07-06 08:25:05.133  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
07-06 08:25:05.133  3721  3767 I jxcore-log: 
,07-06 08:25:07.050  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
07-06 08:25:07.050  3721  3767 I jxcore-log: 
,07-06 08:25:07.062  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
07-06 08:25:07.062  3721  3767 I jxcore-log: 
,07-06 08:25:07.071  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
07-06 08:25:07.071  3721  3767 I jxcore-log: 
,07-06 08:25:07.222  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
07-06 08:25:07.222  3721  3767 I jxcore-log: 
,07-06 08:25:07.247   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=277210, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-06 08:25:07.302  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
07-06 08:25:07.302  3721  3767 I jxcore-log: 
,07-06 08:25:07.356  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
07-06 08:25:07.356  3721  3767 I jxcore-log: 
,07-06 08:25:07.363  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
07-06 08:25:07.363  3721  3767 I jxcore-log: 
,07-06 08:25:07.551  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
07-06 08:25:07.551  3721  3767 I jxcore-log: 
,07-06 08:25:07.572  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
07-06 08:25:07.572  3721  3767 I jxcore-log: 
,07-06 08:25:07.577  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
07-06 08:25:07.577  3721  3767 I jxcore-log: 
,07-06 08:25:07.582  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
07-06 08:25:07.582  3721  3767 I jxcore-log: 
,07-06 08:25:07.598  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
07-06 08:25:07.598  3721  3767 I jxcore-log: 
,07-06 08:25:07.616  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
07-06 08:25:07.616  3721  3767 I jxcore-log: 
,07-06 08:25:07.698  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
07-06 08:25:07.698  3721  3767 I jxcore-log: 
,07-06 08:25:07.704  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
07-06 08:25:07.704  3721  3767 I jxcore-log: 
,07-06 08:25:07.729  3721  3767 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
07-06 08:25:07.729  3721  3767 I jxcore-log: 
,07-06 08:25:07.745  3721  3767 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,07-06 08:25:07.746  3721  3767 I jxcore-log: INFO testUtils: BLE multiple advertisement supported
07-06 08:25:07.746  3721  3767 I jxcore-log: 
,07-06 08:25:22.341  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:25:22.343  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:25:22.383  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-06 08:25:22.383  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-06 08:25:22.383  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:25:22.383  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:25:22.396  2492  3774 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-06 08:25:22.396  2492  3774 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jdm.a(PG:82)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jcs.o(PG:406)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jcn.a(PG:1379)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jcs.i(PG:143)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at blb.a(PG:3937)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at czp.a(PG:18188)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at czp.a(PG:9081)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at czq.run(PG:1686)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:25:22.396  2492  3774 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jdj.a(PG:4091)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jdj.a(PG:1125)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jdm.a(PG:77)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	... 12 more
07-06 08:25:22.396  2492  3774 E HttpOperation: Caused by: faj: BadAuthentication
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at fal.a(PG:38)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	at jdj.a(PG:4089)
07-06 08:25:22.396  2492  3774 E HttpOperation: 	... 14 more
,07-06 08:25:22.435  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-06 08:25:22.435  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-06 08:25:22.435  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-06 08:25:22.435  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:25:22.451  2492  3774 E HttpOperation: [getmobileexperiments] Unexpected exception
07-06 08:25:22.451  2492  3774 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jdm.a(PG:82)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jcs.o(PG:406)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jcn.a(PG:1379)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jcs.i(PG:143)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at hec.a(PG:42)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at hee.a(PG:102)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at czr.a(PG:65)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at kka.a(PG:108)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at czp.a(PG:19176)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at czp.a(PG:9081)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at czq.run(PG:1686)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:25:22.451  2492  3774 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jdj.a(PG:4091)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jdj.a(PG:1125)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jdm.a(PG:77)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	... 15 more
07-06 08:25:22.451  2492  3774 E HttpOperation: Caused by: faj: BadAuthentication
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at fal.a(PG:38)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	at jdj.a(PG:4089)
07-06 08:25:22.451  2492  3774 E HttpOperation: 	... 17 more
07-06 08:25:22.452  2492  3774 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-06 08:25:22.452  2492  3774 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jdm.a(PG:82)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jcs.o(PG:406)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jcn.a(PG:1379)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jcs.i(PG:143)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at hec.a(PG:42)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at hee.a(PG:102)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at czr.a(PG:65)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at kka.a(PG:108)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at czp.a(PG:19176)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at czp.a(PG:9081)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at czq.run(PG:1686)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jdj.a(PG:4091)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jdj.a(PG:1,125)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jdm.a(PG:77)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	... 15 more
07-06 08:25:22.452  2492  3774 E ExperimentLoader: Caused by: faj: BadAuthentication
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at fal.a(PG:38)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	at jdj.a(PG:4089)
07-06 08:25:22.452  2492  3774 E ExperimentLoader: 	... 17 more
,07-06 08:25:22.579   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 291978, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-06 08:25:44.114   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=314077, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:25:49.036  1661  1805 I Keyboard.Facilitator.LanguageModelFlusher: run()
07-06 08:25:49.037  1661  1805 I Keyboard.Facilitator: flushDynamicLanguageModels()
,07-06 08:25:49.077  1500  1500 I ConfigService: onCreate
,07-06 08:25:52.683  3014  3778 V KeepSync: Connecting to GoogleApiClient
,07-06 08:25:52.684   876  1789 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-06 08:25:52.730  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:25:52.732  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:25:52.752  1500  2868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
07-06 08:25:52.753  1500  2868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-06 08:25:52.753  1500  2868 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:25:52.753  1500  2868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:25:52.768  1792  3779 V BaseAuthAsyncOperation: access token request failed
,07-06 08:25:52.769  3014  3778 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-06 08:25:52.815  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-06 08:25:52.815  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
,07-06 08:25:52.815  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:25:52.815  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:25:52.831  3014  3778 E KeepSync: IOException
07-06 08:25:52.831  3014  3778 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-06 08:25:52.831  3014  3778 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-06 08:25:52.831  3014  3778 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-06 08:25:52.831  3014  3778 E KeepSync: 	... 10 more
,07-06 08:25:52.831  3014  3778 W KeepSync: Sync result 2
,07-06 08:25:52.840   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 321836, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-06 08:25:54.148  1500  1500 I ConfigService: onDestroy
,07-06 08:25:59.101   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=329064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-06 08:26:11.860  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:26:11.873  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:26:11.877  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:26:11.932  1500  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
,07-06 08:26:11.932  1500  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
07-06 08:26:11.932  1500  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-06 08:26:11.932  1500  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:26:11.970  1500  2028 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
07-06 08:26:11.970  1500  2028 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
07-06 08:26:11.970  1500  2028 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
07-06 08:26:11.970  1500  2028 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
07-06 08:26:11.970  1500  2028 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
07-06 08:26:11.970  1500  2028 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
07-06 08:26:11.970  1500  2028 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
,07-06 08:26:11.981  3420  3451 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
07-06 08:26:11.981  3420  3451 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
07-06 08:26:11.981  3420  3451 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
07-06 08:26:11.981  3420  3451 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
07-06 08:26:11.981  3420  3451 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
07-06 08:26:11.981  3420  3451 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
07-06 08:26:11.981  3420  3451 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
,07-06 08:26:49.607   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=379570, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:26:58.034   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=387997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-06 08:27:34.834   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=424797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:28:20.274   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=470237, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-06 08:28:57.180   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=507144, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:29:02.901  3479  3790 I BooksSync: Starting books sync for 61035162, extras: ade
,07-06 08:29:02.932  3479  3791 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-06 08:29:02.946  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:29:02.949  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:29:02.984  1500  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-06 08:29:02.985  1500  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-06 08:29:02.985  1500  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-06 08:29:02.985  1500  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:29:03.019  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:29:03.023  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:29:03.054  1500  2868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-06 08:29:03.055  1500  2868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-06 08:29:03.055  1500  2868 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:29:03.055  1500  2868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:29:03.080  3479  3791 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-06 08:29:03.081  3479  3790 E BooksSync: Soft error
07-06 08:29:03.081  3479  3790 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-06 08:29:03.081  3479  3790 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-06 08:29:03.082  3479  3790 E BooksSync: Sync error
07-06 08:29:03.082  3479  3790 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-06 08:29:03.082  3479  3790 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-06 08:29:03.082  3479  3790 I BooksSync: Finished books sync
,07-06 08:29:03.094   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 512821, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-06 08:29:45.392  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:29:45.393  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:29:45.425  1500  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-06 08:29:45.425  1500  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-06 08:29:45.425  1500  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:29:45.425  1500  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:29:45.444  2492  3795 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-06 08:29:45.444  2492  3795 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jdm.a(PG:82)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jcs.o(PG:406)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jcn.a(PG:1379)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jcs.i(PG:143)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at blb.a(PG:3937)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at czp.a(PG:18188)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at czp.a(PG:9081)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at czq.run(PG:1686)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:29:45.444  2492  3795 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jdj.a(PG:4091)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jdj.a(PG:1125)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jdm.a(PG:77)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	... 12 more
07-06 08:29:45.444  2492  3795 E HttpOperation: Caused by: faj: BadAuthentication
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at fal.a(PG:38)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	at jdj.a(PG:4089)
07-06 08:29:45.444  2492  3795 E HttpOperation: 	... 14 more
,07-06 08:29:45.496  1500  2868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-06 08:29:45.496  1500  2868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-06 08:29:45.496  1500  2868 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:29:45.496  1500  2868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:29:45.510  2492  3795 E HttpOperation: [getmobileexperiments] Unexpected exception
07-06 08:29:45.510  2492  3795 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jdm.a(PG:82)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jcs.o(PG:406)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jcn.a(PG:1379)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jcs.i(PG:143)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at hec.a(PG:42)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at hee.a(PG:102)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at czr.a(PG:65)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at kka.a(PG:108)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at czp.a(PG:19176)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at czp.a(PG:9081)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at czq.run(PG:1686)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:29:45.510  2492  3795 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jdj.a(PG:4091)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jdj.a(PG:1125)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jdm.a(PG:77)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	... 15 more
07-06 08:29:45.510  2492  3795 E HttpOperation: Caused by: faj: BadAuthentication
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at fal.a(PG:38)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	at jdj.a(PG:4089)
07-06 08:29:45.510  2492  3795 E HttpOperation: 	... 17 more
,07-06 08:29:45.511  2492  3795 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-06 08:29:45.511  2492  3795 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jdm.a(PG:82)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jcs.o(PG:406)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jcn.a(PG:1379)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jcs.i(PG:143)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at hec.a(PG:42)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at hee.a(PG:102)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at czr.a(PG:65)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at kka.a(PG:108)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at czp.a(PG:19176)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at czp.a(PG:9081)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at czq.run(PG:1686)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jdj.a(PG:4091)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jdj.a(PG:1125)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jdm.a(PG:77)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	... 15 more
07-06 08:29:45.511  2492  3795 E ExperimentLoader: Caused by: faj: BadAuthentication
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at fal.a(PG:38)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	at jdj.a(PG:4089)
07-06 08:29:45.511  2492  3795 E ExperimentLoader: 	... 17 more
,07-06 08:29:45.643   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 555079, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-06 08:30:15.917  3014  3799 V KeepSync: Connecting to GoogleApiClient
,07-06 08:30:15.917   876  1771 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-06 08:30:15.963  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:30:15.964  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:30:15.983  1500  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-06 08:30:15.983  1500  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-06 08:30:15.983  1500  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:30:15.983  1500  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:30:15.998  1792  3800 V BaseAuthAsyncOperation: access token request failed
,07-06 08:30:15.999  3014  3799 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-06 08:30:16.036  1500  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
07-06 08:30:16.036  1500  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-06 08:30:16.036  1500  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:30:16.036  1500  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:30:16.050  3014  3799 E KeepSync: IOException
07-06 08:30:16.050  3014  3799 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-06 08:30:16.050  3014  3799 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-06 08:30:16.050  3014  3799 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-06 08:30:16.050  3014  3799 E KeepSync: 	... 10 more
07-06 08:30:16.050  3014  3799 W KeepSync: Sync result 2
,07-06 08:30:16.067   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 584140, reason: 10079, SyncResult: stats [ numIoExceptions: 1],
,07-06 08:30:17.474   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=587437, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-06 08:30:54.300   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=624263, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:31:17.261   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=647224, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-06 08:31:54.034   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=683997, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:36:00.463  2556  2614 E bt_osi_alarm: reschedule_root_alarm alarm expiration too close for posix timers, switching to guns
,07-06 08:37:33.013  3479  3823 I BooksSync: Starting books sync for 61035162, extras: ade
,07-06 08:37:33.062  3479  3824 I BooksConfig: GmsCore Version = 8.1.86 (2287566-438)
,07-06 08:37:33.090  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:37:33.098  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:37:33.190  1500  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
07-06 08:37:33.191  1500  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
,07-06 08:37:33.191  1500  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:37:33.191  1500  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:37:33.282  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:37:33.288  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:37:33.327  1500  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.books, service: oauth2:https://www.googleapis.com/auth/books
,07-06 08:37:33.327  1500  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/books without consulting the cloud.
07-06 08:37:33.327  1500  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-06 08:37:33.328  1500  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:37:33.347  3479  3824 E BooksAccountManager: auth problem: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
,07-06 08:37:33.348  3479  3823 E BooksSync: Soft error
07-06 08:37:33.348  3479  3823 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-06 08:37:33.348  3479  3823 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
,07-06 08:37:33.348  3479  3823 E BooksSync: Sync error
07-06 08:37:33.348  3479  3823 E BooksSync: com.google.android.gms.auth.UserRecoverableAuthException: BadAuthentication
07-06 08:37:33.348  3479  3823 E BooksSync: com.google.android.gms.auth.GoogleAuthUtil.getToken(Unknown Source)
07-06 08:37:33.349  3479  3823 I BooksSync: Finished books sync
,07-06 08:37:33.368   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.books, POLL, currentRunTime 1022834, reason: AccountsUpdated, SyncResult: stats [ numIoExceptions: 1]
,07-06 08:38:31.154  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:38:31.158  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:38:31.205  1500  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
07-06 08:38:31.206  1500  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
,07-06 08:38:31.206  1500  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:38:31.206  1500  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:38:31.229  2492  3832 E HttpOperation: [jdl{fetchnotificationscount, fetchnotifications, fetchnotifications}] Unexpected exception
07-06 08:38:31.229  2492  3832 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jdm.a(PG:82)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jcs.o(PG:406)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jcn.a(PG:1379)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jcs.i(PG:143)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at blb.a(PG:3937)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at czp.a(PG:18188)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at czp.a(PG:9081)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at czq.run(PG:1686)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:38:31.229  2492  3832 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jdj.a(PG:4091)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jdj.a(PG:1125)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jdm.a(PG:77)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	... 12 more
07-06 08:38:31.229  2492  3832 E HttpOperation: Caused by: faj: BadAuthentication
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at fal.a(PG:38)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	at jdj.a(PG:4089)
07-06 08:38:31.229  2492  3832 E HttpOperation: 	... 14 more
,07-06 08:38:31.323  1500  1511 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.plus, service: oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native
,07-06 08:38:31.323  1500  1511 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/plus.me https://www.googleapis.com/auth/plus.stream.read https://www.googleapis.com/auth/plus.stream.write https://www.googleapis.com/auth/plus.circles.write https://www.googleapis.com/auth/plus.circles.read https://www.googleapis.com/auth/plus.photos.readwrite https://www.googleapis.com/auth/plus.native without consulting the cloud.
07-06 08:38:31.323  1500  1511 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:38:31.323  1500  1511 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:38:31.361  2492  3832 E HttpOperation: [getmobileexperiments] Unexpected exception
07-06 08:38:31.361  2492  3832 E HttpOperation: java.io.IOException: Cannot obtain authentication token
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jdm.a(PG:82)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jcs.o(PG:406)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jcn.a(PG:1379)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jcs.i(PG:143)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at hec.a(PG:42)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at hee.a(PG:102)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at czr.a(PG:65)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at kka.a(PG:108)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at czp.a(PG:19176)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	,at czp.a(PG:9081)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at czq.run(PG:1686)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:38:31.361  2492  3832 E HttpOperation: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jdj.a(PG:4091)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jdj.a(PG:1125)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jdm.a(PG:77)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	... 15 more
07-06 08:38:31.361  2492  3832 E HttpOperation: Caused by: faj: BadAuthentication
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at fal.a(PG:38)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	at jdj.a(PG:4089)
07-06 08:38:31.361  2492  3832 E HttpOperation: 	... 17 more
,07-06 08:38:31.362  2492  3832 E ExperimentLoader: [getmobileexperiments] failed due to exception: java.io.IOException: Cannot obtain authentication token
07-06 08:38:31.362  2492  3832 E ExperimentLoader: java.io.IOException: Cannot obtain authentication token
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jdm.a(PG:82)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jcs.o(PG:406)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jcn.a(PG:1379)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jcs.i(PG:143)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at hec.a(PG:42)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at hee.a(PG:102)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at czr.a(PG:65)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at kka.a(PG:108)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at czp.a(PG:19176)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at czp.a(PG:9081)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at czq.run(PG:1686)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:423)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at java.lang.Thread.run(Thread.java:818)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: Caused by: android.accounts.AuthenticatorException: Recoverable error
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jdj.a(PG:4091)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jdj.a(PG:1125)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jdm.a(PG:77)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	... 15 more
07-06 08:38:31.362  2492  3832 E ExperimentLoader: Caused by: faj: BadAuthentication
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at fal.a(PG:38)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	at jdj.a(PG:4089)
07-06 08:38:31.362  2492  3832 E ExperimentLoader: 	... 17 more
,07-06 08:38:31.487   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.apps.plus.content.EsProvider, PERIODIC, currentRunTime 1080679, reason: Periodic, SyncResult: stats [ numIoExceptions: 1]
,07-06 08:39:01.670  3014  3835 V KeepSync: Connecting to GoogleApiClient
07-06 08:39:01.671   876  3077 W AppOps  : Bad call: specified package com.google.android.gms under uid 10079 but it is really 10011
,07-06 08:39:01.732  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:39:01.736  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:39:01.781  1500  1512 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata
,07-06 08:39:01.781  1500  1512 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/drive https://www.googleapis.com/auth/drive.appdata without consulting the cloud.
07-06 08:39:01.781  1500  1512 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:39:01.781  1500  1512 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:39:01.811  1792  3836 V BaseAuthAsyncOperation: access token request failed
,07-06 08:39:01.813  3014  3835 V KeepSync: GoogleApiClient failed to connect with error code: 4
,07-06 08:39:01.882  1500  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.keep, service: oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive
,07-06 08:39:01.882  1500  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/memento https://www.googleapis.com/auth/drive without consulting the cloud.
07-06 08:39:01.882  1500  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:39:01.882  1500  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:39:01.908  3014  3835 E KeepSync: IOException
07-06 08:39:01.908  3014  3835 E KeepSync: com.google.android.apiary.AuthenticationException: Could not get an auth token
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:152)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.intercept(SourceFile:89)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient$KeepRequestInitializer.intercept(SourceFile:238)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.api.client.http.HttpRequest.execute(SourceFile:858)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:410)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.executeUnparsed(SourceFile:343)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.api.client.googleapis.services.AbstractGoogleClientRequest.execute(SourceFile:460)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.keep.util.KeepApiaryClient.syncChanges(SourceFile:212)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.syncOnceToServer(SourceFile:304)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.keep.syncadapter.KeepSyncAdapter.onPerformSync(SourceFile:195)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:272)
07-06 08:39:01.908  3014  3835 E KeepSync: Caused by: com.google.android.gms.auth.UserRecoverableNotifiedException: User intervention required. Notification has been pushed.
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.zzc(Unknown)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.gms.auth.GoogleAuthUtil.getTokenWithNotification(Unknown)
07-06 08:39:01.908  3014  3835 E KeepSync: 	at com.google.android.apiary.GoogleRequestInitializer.getAuthToken(SourceFile:140)
07-06 08:39:01.908  3014  3835 E KeepSync: 	... 10 more
07-06 08:39:01.908  3014  3835 W KeepSync: Sync result 2
,07-06 08:39:01.923   876   888 D SyncManager: failed sync operation thalitester@gmail.com u0 (com.google), com.google.android.keep, LOCAL, currentRunTime 1108703, reason: 10079, SyncResult: stats [ numIoExceptions: 1]
,07-06 08:39:04.402   876  1295 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
,07-06 08:39:04.402   876  1295 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,07-06 08:39:33.291  1500  1947 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-06 08:40:48.808   876   888 I UsageStatsService: User[0] Flushing usage stats to disk
,07-06 08:42:07.511   876  1767 I ActivityManager: Start proc 3863:com.google.android.youtube/u0a86 for service com.google.android.youtube/com.google.android.libraries.youtube.common.gcore.gcoreclient.gcm.impl.GcmTaskServiceDelegator
,07-06 08:42:07.554   876  1828 I ActivityManager: Start proc 3875:com.google.android.apps.gcs/u0a89 for service com.google.android.apps.gcs/com.google.android.flib.nova.experiment.ExperimentUpdateService
,07-06 08:42:07.595  3875  3875 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm
,07-06 08:42:07.597  3863  3863 W System  : ClassLoader referenced unknown path: /system/app/YouTube/lib/arm
,07-06 08:42:07.653  3875  3875 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,07-06 08:42:07.690  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:42:07.696  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:42:07.709  3863  3897 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,07-06 08:42:07.771  3875  3899 V GoogleAuthProtoRequest: [321] a.<init>: mAccountName set to: thalitester@gmail.com
,07-06 08:42:07.818  3863  3897 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
,07-06 08:42:07.912  3863  3897 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-06 08:42:07.939  1500  2028 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-06 08:42:07.939  1500  2028 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-06 08:42:07.939  1500  2028 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-06 08:42:07.939  1500  2028 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:42:07.985  3863  3863 W System.err: YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: [321] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: [321] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-06 08:42:07.995  3875  3899 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-06 08:42:08.000   876  1767 I ActivityManager: Killing 2855:com.google.android.calendar/u0a37 (adj 15): empty #17
,07-06 08:42:08.279  3863  3863 W InstanceID/Rpc: Found 10011
,07-06 08:42:08.345  3916  3916 I dex2oat : /system/bin/dex2oat --dex-file=/data/user/0/com.google.android.youtube/cache/ads-1620036282.jar --oat-file=/data/user/0/com.google.android.youtube/cache/ads-1620036282.dex
,07-06 08:42:08.477  3916  3916 I dex2oat : dex2oat took 181.221ms (threads: 4) arena alloc=143KB java alloc=29KB native alloc=1258KB free=1301KB
,07-06 08:42:08.528   876   887 I ActivityManager: Killing 2394:com.google.android.talk/u0a61 (adj 15): empty #17
,07-06 08:42:12.354   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1302317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,07-06 08:42:30.834   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1320797, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:42:38.458  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:42:38.460  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:42:38.472  3875  3974 V GoogleAuthProtoRequest: [322] a.<init>: mAccountName set to: thalitester@gmail.com
,07-06 08:42:38.514  1500  2052 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-06 08:42:38.514  1500  2052 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-06 08:42:38.514  1500  2052 I GLSUser : [GLSUser] Extracting token using key: Auth
,07-06 08:42:38.514  1500  2052 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:42:38.527  3875  3974 W ExperimentUpdateService: [322] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: [322] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-06 08:42:38.528  3875  3974 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-06 08:43:38.738  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:43:38.746  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:43:38.759  3875  3985 V GoogleAuthProtoRequest: [323] a.<init>: mAccountName set to: thalitester@gmail.com
,07-06 08:43:38.787  1500  2868 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
,07-06 08:43:38.787  1500  2868 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-06 08:43:38.787  1500  2868 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:43:38.787  1500  2868 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: [323] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: [323] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-06 08:43:38.811  3875  3985 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-06 08:45:38.929  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:45:38.930  1500  1500 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,07-06 08:45:38.947  3875  4004 V GoogleAuthProtoRequest: [324] a.<init>: mAccountName set to: thalitester@gmail.com
,07-06 08:45:38.976  1500  1884 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
07-06 08:45:38.976  1500  1884 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
07-06 08:45:38.976  1500  1884 I GLSUser : [GLSUser] Extracting token using key: Auth
07-06 08:45:38.976  1500  1884 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,07-06 08:45:39.006  3875  4004 W ExperimentUpdateService: [324] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
,07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: [324] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
07-06 08:45:39.007  3875  4004 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
,07-06 08:46:05.958   876  1295 E qti_sensors_hal: waitForResponse: pthread_cond_timedwait() rc=110 (cond: 0)
,07-06 08:46:05.959   876  1295 E qti_sensors_hal: deactivateDpc: ERROR: No response from the request
,07-06 08:46:09.406   876  1302 I PowerManagerService: Waking up from dozing (uid 1000)...
,07-06 08:46:09.407   876   876 V KeyguardServiceDelegate: onStartedWakingUp()
,07-06 08:46:09.409   876   896 I DisplayPowerController: Blocking screen on until initial contents have been drawn.
,07-06 08:46:09.415   876   896 V KeyguardServiceDelegate: onScreenTurnedOn(showListener = com.android.server.policy.PhoneWindowManager$2@a92b5a8)
,07-06 08:46:09.416  3721  3721 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-06 08:46:09.416  3721  3721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STARTED
,07-06 08:46:09.421   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", ON
07-06 08:46:09.422   281   281 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6aa4000
07-06 08:46:09.422   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 2 on display: 0
07-06 08:46:09.432   876  1380 V KeyguardServiceDelegate: **** SHOWN CALLED ****
07-06 08:46:09.437   876  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,07-06 08:46:09.443   876  1310 E native  : do suspend false
,07-06 08:46:09.447  1692  1692 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,07-06 08:46:09.450   876  1310 D WifiConfigStore: No blacklist allowed without epno enabled
,07-06 08:46:09.454  1748  1877 E BrcmNfcJni: nfaConnectionCallback: unknown event ????
,07-06 08:46:09.454  1748  1877 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_TECH_CFG_EVT; status=0x0
,07-06 08:46:09.454  1748  1877 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_SET_PROTO_CFG_EVT; status=0x0
07-06 08:46:09.455  1748  1873 D BrcmNfcJni: RoutingManager::commitRouting
07-06 08:46:09.455  1748  1877 D BrcmNfcJni: RoutingManager::nfaEeCallback: NFA_EE_UPDATED_EVT
07-06 08:46:09.455  3721  3721 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
07-06 08:46:09.455  3721  3721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: RESUMED
07-06 08:46:09.460   377  1281 D audio_hw_primary: adev_set_parameters: enter: screen_state=on
,07-06 08:46:09.460   377  1281 D mot_vr_audio_hw: adev_set_parameters: screen_state=on
,07-06 08:46:09.473   876  1712 I ActivityManager: Start proc 4012:com.google.android.apps.fitness/u0a51 for broadcast com.google.android.apps.fitness/.widget.TodayStatusWidgetProvider
,07-06 08:46:09.520  4012  4012 W System  : ClassLoader referenced unknown path: /system/app/FitnessPrebuilt/lib/arm
,07-06 08:46:09.535   876  1771 I ActivityManager: Killing 3290:com.google.android.music:main/u0a66 (adj 15): empty #17
,07-06 08:46:09.596   876   896 I DisplayPowerController: Unblocked screen on after 188 ms
,07-06 08:46:09.597   876   896 V KeyguardServiceDelegate: onScreenTurnedOn()
07-06 08:46:09.597   876   896 I DreamManagerService: Gently waking up from dream.
,07-06 08:46:09.598   876   886 I DreamManagerService: Leaving dreamland.
07-06 08:46:09.599   876   891 I DreamController: Stopping dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-06 08:46:09.666   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-06 08:46:09.666   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 2 on display 0
,07-06 08:46:09.669   876  1336 D SurfaceControl: Excessive delay in setPowerMode(): 248ms
,07-06 08:46:10.217  1748  2106 D NfcService: Discovery configuration equal, not updating.
,07-06 08:46:14.447   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1544410, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,07-06 08:46:24.967   876  2150 D NetlinkSocketObserver: NeighborEvent{elapsedMs=1554930, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,07-06 08:48:09.490  1692  2349 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-06 08:48:11.343   876   896 I PowerManagerService: Going to sleep due to screen timeout (uid 1000)...
,07-06 08:48:11.354  1661  1661 I Keyboard.Facilitator: onFinishInput()
,07-06 08:48:11.916  3721  3721 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-06 08:48:11.916  3721  3721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: PAUSED
,07-06 08:48:11.946   876   896 V KeyguardServiceDelegate: onScreenTurnedOff()
,07-06 08:48:11.947  3721  3721 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3fedd90 Bundle[{plugin=Bundle[{}], android:viewHierarchyState=Bundle[{android:views={100=android.view.AbsSavedState$1@9ca4d41, 16908290=android.view.AbsSavedState$1@9ca4d41}, android:focusedViewId=100}]}]
07-06 08:48:11.947  3721  3721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: SAVE_INSTANCE_STATE
07-06 08:48:11.947  3721  3721 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
07-06 08:48:11.947  3721  3721 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: STOPPED
,07-06 08:48:11.972   876   894 I DisplayManagerService: Display device changed state: "Built-in Screen", OFF
07-06 08:48:11.975   281   281 D SurfaceFlinger: Set power mode=0, type=0 flinger=0xb6aa4000
07-06 08:48:11.975   281   281 D qdhwcomposer: hwc_setPowerMode: Setting mode 0 on display: 0
,07-06 08:48:11.983   876   885 I art     : Background partial concurrent mark sweep GC freed 38670(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 29MB/43MB, paused 1.974ms total 106.041ms
,07-06 08:48:12.219   281   342 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-06 08:48:12.223   281   281 D qdhwcomposer: hwc_setPowerMode: Done setting mode 0 on display 0
,07-06 08:48:12.223   876  1336 D SurfaceControl: Excessive delay in setPowerMode(): 251ms
,07-06 08:48:12.234   876   896 I DreamManagerService: Entering dreamland.
07-06 08:48:12.234   876   896 I PowerManagerService: Dozing...
,07-06 08:48:12.236   876   891 I DreamController: Starting dream: name=ComponentInfo{com.android.systemui/com.android.systemui.doze.DozeService}, isTest=false, canDoze=true, userId=0
,07-06 08:48:12.318   876  1310 D WifiConfigStore: Retrieve network priorities after PNO.
,07-06 08:48:12.333   876  1310 E native  : do suspend true
,07-06 08:48:12.438   377   377 D audio_hw_primary: adev_set_parameters: enter: screen_state=off
,07-06 08:48:12.438   377   377 D mot_vr_audio_hw: adev_set_parameters: screen_state=off
,TIME-OUT KILL (timeout was 1400000ms)
```
