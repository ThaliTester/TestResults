#### Test 794266509fa1f7f_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-05 02:13:21.178  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-05 02:13:21.189  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-05 02:13:21.191  1498  1498 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-05 02:13:21.230  1498  1925 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.android.vending, service: androidmarket
08-05 02:13:21.230  1498  1925 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> androidmarket without consulting the cloud.
08-05 02:13:21.230  1498  1925 I GLSUser : [GLSUser] Extracting token using key: Auth
08-05 02:13:21.230  1498  1925 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-05 02:13:21.262  1498  1925 W GLSActivity: com.google.android.gms.auth.af: User intervention required. Notification has been pushed.
08-05 02:13:21.262  1498  1925 W GLSActivity: 	at com.google.android.gms.auth.p.e(SourceFile:1411)
08-05 02:13:21.262  1498  1925 W GLSActivity: 	at com.google.android.gms.auth.p.d(SourceFile:637)
08-05 02:13:21.262  1498  1925 W GLSActivity: 	at com.google.android.gms.auth.be.m.getAuthToken(SourceFile:177)
08-05 02:13:21.262  1498  1925 W GLSActivity: 	at android.accounts.AbstractAccountAuthenticator$Transport.getAuthToken(AbstractAccountAuthenticator.java:214)
08-05 02:13:21.262  1498  1925 W GLSActivity: 	at android.accounts.IAccountAuthenticator$Stub.onTransact(IAccountAuthenticator.java:113)
08-05 02:13:21.262  1498  1925 W GLSActivity: 	at android.os.Binder.execTransact(Binder.java:453)
08-05 02:13:21.272  3370  3399 E PlayEventLogger: Failed to get auth token: User intervention required. Notification has been pushed.
08-05 02:13:21.272  3370  3399 E PlayEventLogger: android.accounts.AuthenticatorException: User intervention required. Notification has been pushed.
08-05 02:13:21.272  3370  3399 E PlayEventLogger: 	at android.accounts.AccountManager.convertErrorToException(AccountManager.java:2150)
08-05 02:13:21.272  3370  3399 E PlayEventLogger: 	at android.accounts.AccountManager.-wrap0(AccountManager.java)
08-05 02:13:21.272  3370  3399 E PlayEventLogger: 	at android.accounts.AccountManager$AmsTask$Response.onError(AccountManager.java:1993)
08-05 02:13:21.272  3370  3399 E PlayEventLogger: 	at android.accounts.IAccountManagerResponse$Stub.onTransact(IAccountManagerResponse.java:69)
08-05 02:13:21.272  3370  3399 E PlayEventLogger: 	at android.os.Binder.execTransact(Binder.java:453)
08-05 02:13:21.895  3689  3689 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-05 02:13:21.900  3689  3689 D AndroidRuntime: CheckJNI is OFF
08-05 02:13:21.943  3689  3689 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-05 02:13:21.993  3689  3689 I Radio-JNI: register_android_hardware_Radio DONE
08-05 02:13:22.015  3689  3689 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-05 02:13:22.025   872  1759 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 02:13:22.085   872  1759 I ActivityManager: Start proc 3702:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-05 02:13:22.088  3689  3689 D AndroidRuntime: Shutting down VM
08-05 02:13:22.169  3702  3702 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-05 02:13:22.201  3702  3702 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-05 02:13:22.209  3702  3702 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3011-3014)
08-05 02:13:22.209  3702  3702 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 02:13:22.223  3702  3702 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b82b203}
08-05 02:13:22.223  3702  3702 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 02:13:22.224  3702  3702 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-05 02:13:22.231  3702  3702 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-05 02:13:22.232  3702  3702 E SysUtils: ApplicationContext is null in ApplicationStatus
08-05 02:13:22.248  3702  3702 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-05 02:13:22.258  3702  3702 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 02:13:22.259  3702  3702 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-05 02:13:22.259  3702  3702 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-05 02:13:22.259  3702  3702 I Adreno  : Build Date                       : 10/20/15
08-05 02:13:22.259  3702  3702 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-05 02:13:22.259  3702  3702 I Adreno  : Local Branch                     : M14
08-05 02:13:22.259  3702  3702 I Adreno  : Remote Branch                    : 
08-05 02:13:22.259  3702  3702 I Adreno  : Remote Branch                    : 
08-05 02:13:22.259  3702  3702 I Adreno  : Reconstruct Branch               : 
,08-05 02:13:22.332   872   889 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ec5524:true
,08-05 02:13:22.379  3702  3702 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 02:13:22.390  3702  3702 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-05 02:13:22.471  3702  3739 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-05 02:13:22.486  3702  3726 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-05 02:13:22.532  3702  3739 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 02:13:22.592   872   890 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +469ms (total +527ms)
,08-05 02:13:22.595  1654  1654 I Keyboard.Facilitator: onFinishInput()
,08-05 02:13:22.663  3702  3702 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3702
,08-05 02:13:22.783  3702  3702 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 02:13:22.979  3702  3741 D jxcore_app_log: JniHelper::setJavaVM(0xb4dbc000), pthread_self() = -1681393360
,08-05 02:13:22.984  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 02:13:22.984  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 02:13:22.984  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 02:13:22.984  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 02:13:22.984  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 02:13:22.984  3702  3741 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@683bb96 added. We now have 1 listener(s)
,08-05 02:13:22.988  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-05 02:13:22.993  3702  3741 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
,08-05 02:13:22.996  3702  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 02:13:22.997  3702  3741 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 02:13:23.008  3702  3741 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@827f0ed added. We now have 1 listener(s)
,08-05 02:13:23.010  3702  3741 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 02:13:23.016   872  1306 D WifiService: New client listening to asynchronous messages
,08-05 02:13:23.018  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 02:13:23.019  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 02:13:23.019  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-05 02:13:23.020  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-05 02:13:23.020  3702  3741 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 02:13:23.032  3702  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 02:13:23.033  3702  3741 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-05 02:13:23.043  3702  3741 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:13:23.043  3702  3741 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 02:13:23.043  3702  3741 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 02:13:23.043  3702  3741 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 02:13:23.044  3702  3741 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 02:13:23.048  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 02:13:23.051  3702  3702 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 02:13:23.080  3702  3702 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 02:13:24.030  3702  3749 W jxcore-log: Initializing JXcore engine
,08-05 02:13:24.030  3702  3749 W jxcore-log: JXcore engine is ready
,08-05 02:13:24.066  3749  3749 W Thread-330: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8931 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-05 02:13:24.066  3749  3749 W Thread-330: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[9679]" dev="sockfs" ino=9679 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-05 02:13:24.066  3749  3749 W Thread-330: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-05 02:13:24.066  3749  3749 W Thread-330: type=1400 audit(0.0:8): avc: denied { ioctl } for path="socket:[27699]" dev="sockfs" ino=27699 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-05 02:13:24.081  3702  3749 W jxcore-log: Starting JXcore engine
,08-05 02:13:24.163  3702  3749 W jxcore-log: Platform android
08-05 02:13:24.163  3702  3749 W jxcore-log: 
,08-05 02:13:24.163  3702  3749 W jxcore-log: Process ARCH arm
08-05 02:13:24.163  3702  3749 W jxcore-log: 
,08-05 02:13:24.384  3702  3749 I jxcore-log: JXcore Cordova bridge is ready!
08-05 02:13:24.384  3702  3749 I jxcore-log: 
,08-05 02:13:24.384  3702  3749 W jxcore-log: JXcore engine is started
,08-05 02:13:24.392  3702  3741 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 02:13:24.397  3702  3702 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 02:13:39.750  3702  3749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 02:13:39.750  3702  3749 I jxcore-log: 
,08-05 02:13:39.753  3702  3749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 02:13:39.753  3702  3749 I jxcore-log: 
,08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:13:39.766  3702  3749 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 02:13:39.772  3702  3749 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 02:13:39.774  3702  3749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 02:13:39.774  3702  3749 I jxcore-log: 
,08-05 02:13:39.775  3702  3749 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 02:13:39.775  3702  3749 I jxcore-log: 
,08-05 02:13:40.109  3702  3749 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
,08-05 02:13:40.109  3702  3749 I jxcore-log: Failed to execute UT.
08-05 02:13:40.109  3702  3749 I jxcore-log: 
08-05 02:13:40.109  3702  3749 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-05 02:13:40.109  3702  3749 I jxcore-log: 
,08-05 02:13:40.112  3702  3749 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 02:13:40.112  3702  3749 I jxcore-log: 
,08-05 02:13:40.137  3702  3702 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 02:13:40.765  3750  3750 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-05 02:13:40.770  3750  3750 D AndroidRuntime: CheckJNI is OFF
,08-05 02:13:40.805  3750  3750 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-05 02:13:40.846  3750  3750 I Radio-JNI: register_android_hardware_Radio DONE
,08-05 02:13:40.867  3750  3750 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 02:13:40.879   872   885 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
,08-05 02:13:40.880   872   885 I ActivityManager: Killing 3702:com.test.thalitest/u0a0 (adj 0): stop com.test.thalitest
,08-05 02:13:40.949   872  1295 W InputDispatcher: channel '8a14f54 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,08-05 02:13:40.949   872  1295 E InputDispatcher: channel '8a14f54 com.test.thalitest/com.test.thalitest.MainActivity (server)' ~ Channel is unrecoverably broken and will be disposed!
,08-05 02:13:40.962   872  1761 D GraphicsStats: Buffer count: 2
,08-05 02:13:40.962   872   883 I WindowState: WIN DEATH: Window{8a14f54 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-05 02:13:40.962   872   883 W InputDispatcher: Attempted to unregister already unregistered input channel '8a14f54 com.test.thalitest/com.test.thalitest.MainActivity (server)'
08-05 02:13:40.963   872  1306 D WifiService: Client connection lost with reason: 4
,08-05 02:13:40.995   872   895 W PackageSettings: Skipping PackageSetting{6c9a3ce com.example.hello/10273} due to missing metadata
,08-05 02:13:41.023   872   885 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-05 02:13:41.023   872   885 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-05 02:13:41.024   872   885 E ActivityManager: Failure starting process com.test.thalitest
08-05 02:13:41.024   872   885 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-05 02:13:41.024   872   885 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.024   872   885 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.024   872   885 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:41.024   872   885 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 02:13:41.024   872   885 I ActivityManager:   Force finishing activity ActivityRecord{2971f19 u0 com.test.thalitest/.MainActivity t2}
,08-05 02:13:41.025   872   895 I art     : Starting a blocking GC Explicit
,08-05 02:13:41.034   872  1761 W ActivityManager: Spurious death for ProcessRecord{1b5e2bb 0:com.test.thalitest/u0a0}, curProc for 3702: null
,08-05 02:13:41.077   872   895 I art     : Explicit concurrent mark sweep GC freed 18212(1276KB) AllocSpace objects, 5(100KB) LOS objects, 33% free, 28MB/43MB, paused 807us total 51.396ms
,08-05 02:13:41.088   872   895 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-05 02:13:41.090  3750  3750 I art     : System.exit called, status: 0
08-05 02:13:41.090  3750  3750 I AndroidRuntime: VM exiting with result code 0.
08-05 02:13:41.093   872   895 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-05 02:13:41.110   872   885 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-05 02:13:41.116  2537  2537 D BluetoothMapAppObserver: onReceive
,08-05 02:13:41.116  2537  2537 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-05 02:13:41.119  1833  2021 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 02:13:41.124   872  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-05 02:13:41.125  3509  3509 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-05 02:13:41.145  1654  1654 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-05 02:13:41.148  1654  3763 I Keyboard.Facilitator.DecoderInitializer: run()
,08-05 02:13:41.159  1734  1734 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-05 02:13:41.167  1654  3763 I Decoder : createOrResetDecoder
,08-05 02:13:41.177  3350  3764 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-05 02:13:41.192  1498  1498 I ConfigService: onCreate
,08-05 02:13:41.204   872   872 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-05 02:13:41.220  1498  1498 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-05 02:13:41.220  1498  1498 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-05 02:13:41.222  1654  3763 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-05 02:13:41.229  1752  1830 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-05 02:13:41.239  3350  3764 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,08-05 02:13:41.241   872   884 E PackageManager: Failed to write settings, restoring backup
08-05 02:13:41.241   872   884 E PackageManager: java.io.IOException: write failed: EROFS (Read-only file system)
08-05 02:13:41.241   872   884 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:498)
08-05 02:13:41.241   872   884 E PackageManager: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
08-05 02:13:41.241   872   884 E PackageManager: 	at java.io.OutputStreamWriter.flushBytes(OutputStreamWriter.java:170)
08-05 02:13:41.241   872   884 E PackageManager: 	at java.io.OutputStreamWriter.convert(OutputStreamWriter.java:184)
08-05 02:13:41.241   872   884 E PackageManager: 	at java.io.OutputStreamWriter.write(OutputStreamWriter.java:269)
08-05 02:13:41.241   872   884 E PackageManager: 	at java.io.BufferedWriter.write(BufferedWriter.java:288)
08-05 02:13:41.241   872   884 E PackageManager: 	at java.io.Writer.write(Writer.java:141)
08-05 02:13:41.241   872   884 E PackageManager: 	at org.kxml2.io.KXmlSerializer.attribute(KXmlSerializer.java:465)
08-05 02:13:41.241   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissions(Settings.java:4812)
08-05 02:13:41.241   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4645)
08-05 02:13:41.241   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-05 02:13:41.241   872   884 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-05 02:13:41.241   872   884 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.241   872   884 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.241   872   884 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:41.241   872   884 E PackageManager: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
08-05 02:13:41.241   872   884 E PackageManager: 	at libcore.io.Posix.writeBytes(Native Method)
08-05 02:13:41.241   872   884 E PackageManager: 	at libcore.io.Posix.write(Posix.java:271)
08-05 02:13:41.241   872   884 E PackageManager: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
08-05 02:13:41.241   872   884 E PackageManager: 	at libcore.io.IoBridge.write(IoBridge.java:493)
08-05 02:13:41.241   872   884 E PackageManager: 	... 14 more
,08-05 02:13:41.242   872  1747 I ActivityManager: Start proc 3768:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-05 02:13:41.242  1752  1830 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-05 02:13:41.242  1752  1830 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1752
08-05 02:13:41.242  1752  1830 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.242  1752  1830 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:41.242  3350  3764 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-05 02:13:41.242  3350  3764 E AndroidRuntime: Process: android.process.acore, PID: 3350
08-05 02:13:41.242  3350  3764 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.242  3350  3764 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:41.245   872   885 E DropBoxManagerService: Can't write: system_server_wtf
08-05 02:13:41.245   872   885 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-05 02:13:41.245   872   885 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 02:13:41.245   872   885 E DropBoxManagerService: 	... 13 more
08-05 02:13:41.246   872   882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 02:13:41.246   872  3775 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:13:41.246   872  3775 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:13:41.246   872  37,75 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 02:13:41.246   872  3775 E DropBoxManagerService: 	... 5 more
08-05 02:13:41.249   872  3774 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:13:41.249   872  3774 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop107.tmp: open failed: EROFS (Read-only file system)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 02:13:41.249   872  3774 E DropBoxManagerService: 	... 5 more
08-05 02:13:41.250  1752  1830 I Process : Sending signal. PID: 1752 SIG: 9
08-05 02:13:41.265  3350  3764 I Process : Sending signal. PID: 3350 SIG: 9
08-05 02:13:41.280  1848  3782 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-05 02:13:41.280  1848  3782 D AccountUtils: Clearing selected account for com.test.thalitest
,08-05 02:13:41.291  1654  3763 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
,08-05 02:13:41.293  1654  3763 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-05 02:13:41.293  1654  3763 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-05 02:13:41.299  1654  3763 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-05 02:13:41.301  1654  3763 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-05 02:13:41.302  1654  3763 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-05 02:13:41.302  1654  3763 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-05 02:13:41.302   279   279 E lowmemorykiller: Error writing /proc/3350/oom_score_adj; errno=22
08-05 02:13:41.303   279   279 E lowmemorykiller: Error writing /proc/3350/oom_score_adj; errno=22
08-05 02:13:41.304  1848  3782 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-05 02:13:41.307   872   883 D GraphicsStats: Buffer count: 1
08-05 02:13:41.307   872  1747 I WindowState: WIN DEATH: Window{d5115fa u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,08-05 02:13:41.312   872  1365 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1752) has died
,08-05 02:13:41.313   872  1365 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-05 02:13:41.318  1654  3763 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
,08-05 02:13:41.318  1654  3763 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-05 02:13:41.318  1654  3763 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-05 02:13:41.320  1654  3763 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.321  1848  3782 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.322  1848  3782 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:41.323  1848  3782 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-05 02:13:41.320  1654  3763 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-05 02:13:41.325  1654  3763 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-05 02:13:41.349  1848  1848 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-05 02:13:41.349  1848  1848 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-05 02:13:41.354  1848  1848 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,08-05 02:13:41.354  1848  1848 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-05 02:13:41.363  1848  3789 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 02:13:41.363  1848  3789 E DriveAsyncService: disk I/O error (code 3850)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.k(SourceFile:483)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at com.google.android.gms.drive.database.k.b(SourceFile:458)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at com.google.android.gms.drive.database.f.i(SourceFile:1501)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at com.google.android.gms.drive.api.a.bj.a(SourceFile:16)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 02:13:41.363  1848  3789 E DriveAsyncService: 	at java.lang.Thread.run(Thread.java:818)
,08-05 02:13:41.366   279   279 E lowmemorykiller: Error writing /proc/3350/oom_score_adj; errno=22
,08-05 02:13:41.374  1848  3794 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 02:13:41.385  1848  3790 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/metrics.db'.
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.385  1848  3790 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: Couldn't open metrics.db for writing (will try read-only):
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.a(SourceFile:102)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.c.a.b(SourceFile:52)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.metrics.c.c(SourceFile:278)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService.onHandleIntent(SourceFile:51)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.385  1848  3790 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:41.397  1848  3794 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-05 02:13:41.397  1848  3794 E AndroidRuntime: Process: com.google.android.gms, PID: 1848
08-05 02:13:41.397  1848  3794 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-05 02:13:41.397  1848  3794 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-05 02:13:41.400   872   883 I ActivityManager: Start proc 3797:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-05 02:13:41.403  1802  3793 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-05 02:13:41.407   872  3802 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:13:41.407   872  3802 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 02:13:41.407   872  3802 E DropBoxManagerService: 	... 5 more
08-05 02:13:41.419  1848  3794 I Process : Sending signal. PID: 1848 SIG: 9
,08-05 02:13:41.456  1802  3793 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 02:13:41.466  1802  3793 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-05 02:13:41.466  1802  3793 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-05 02:13:41.466  1802  3793 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1802
08-05 02:13:41.466  1802  3793 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.466  1802  3793 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 02:13:41.467   872   883 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-05 02:13:41.468   872   883 I ActivityManager: Killing 1802:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
,08-05 02:13:41.472   872  3810 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:13:41.472   872  3810 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop110.tmp: open failed: EROFS (Read-only file system)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 02:13:41.472   872  3810 E DropBoxManagerService: 	... 5 more
,08-05 02:13:41.499   872  1759 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@8829a5b)
,08-05 02:13:41.500   872  1307 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:41.501   872  1307 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 02:13:41.531  3797  3797 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 02:13:41.531  3797  3797 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-05 02:13:41.532  3797  3797 D AndroidRuntime: Shutting down VM
,08-05 02:13:41.549   872  1306 D WifiService: Client connection lost with reason: 4
,08-05 02:13:41.554   872   883 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-05 02:13:41.559   279   279 E lowmemorykiller: Error opening /proc/1848/oom_score_adj; errno=2
08-05 02:13:41.559   279   279 E lowmemorykiller: Error opening /proc/3350/oom_score_adj; errno=2
,08-05 02:13:41.565   872  1759 I ActivityManager: Process android.process.acore (pid 3350) has died
,08-05 02:13:41.565   872  1759 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,08-05 02:13:41.567  3768  3768 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
08-05 02:13:41.567   872  1604 I ActivityManager: Process com.google.android.gms (pid 1848) has died
,08-05 02:13:41.568   872  1604 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.analytics.service.AnalyticsService in 1000ms
08-05 02:13:41.568   872  1604 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.appstate.service.AppStateIntentService in 11000ms
08-05 02:13:41.568   872  1604 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms
08-05 02:13:41.568   872  1604 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.googlehelp.service.ClearHelpHistoryIntentService in 10999ms
,08-05 02:13:41.569   872  1604 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.app.service.PackageBroadcastService in 10999ms
08-05 02:13:41.569   872  1604 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.drive.api.DriveAsyncService in 10998ms
,08-05 02:13:41.569   872  1604 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 10998ms
,08-05 02:13:41.572   872  1747 W ActivityManager: Spurious death for ProcessRecord{aa11246 0:com.google.android.googlequicksearchbox:search/u0a28}, curProc for 1802: null
,08-05 02:13:41.574  3797  3797 E AndroidRuntime: FATAL EXCEPTION: main
08-05 02:13:41.574  3797  3797 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3797
08-05 02:13:41.574  3797  3797 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5156)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-05 02:13:41.574  3797  3797 E AndroidRuntime: 	... 10 more
08-05 02:13:41.577   872  1680 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-05 02:13:41.578   872  3813 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:13:41.578   872  3813 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-05 02:13:41.578   872  3813 E DropBoxManagerService: 	... 5 more
08-05 02:13:41.580  3797  3797 I Process : Sending signal. PID: 3797 SIG: 9
08-05 02:13:41.594   872  1759 I ActivityManager: Start proc 3814:com.google.android.gms/u0a11 for service com.google.android.gms/.feedback.FeedbackService
,08-05 02:13:41.606   872  1604 I ActivityManager: Start proc 3825:com.android.keychain/1000 for broadcast com.android.keychain/.KeyChainBroadcastReceiver
,08-05 02:13:41.609   872  1761 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3797) has died
,08-05 02:13:41.608   281   341 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
